<script setup>
import Menu from '@/views/layout/menu'
</script>

<template>
  <div class="app-wrapper">
    <el-container>
      <el-aside width="200px" class="sidebar-container"><Menu /></el-aside>
      <el-container>
        <el-header>Header</el-header> <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<style lang="scss" scoped>
.app-wrapper {
  position: relative;
  width: 100%;
  height: 100%;
}
.sidebar-container {
  background-color: #2d3a4b;
  height: 100%;
}
::v-deep .el-container {
  height: 100%;
}
</style>

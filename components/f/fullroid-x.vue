<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zjvjnjj8l"/><path class="ir1399b6e"/><rect class="ojcfe_buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fullroid-x" /></template>
<style>
.ir1399b6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.145 40.062v-5.689h1.862c1.053 0 1.906.856 1.906 1.91s-.853 1.911-1.906 1.911h-1.862m6.1 1.868v-5.689h1.862a1.91 1.91 0 0 1 0 3.821h-1.862m1.862 0l1.863 1.867");
}

.ojcfe_buk {
  width: 3.769px;
  height: 5.689px;
  x: 36.346px;
  y: 34.373px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.884px;
  ry: 1.884px;
}

.zjvjnjj8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.009 5.5H18.99c-.747 0-1.352.606-1.352 1.353v8.34c0 .342.129.67.36.92l5.175 5.577c.446.48 1.206.48 1.652 0L30 16.114a1.35 1.35 0 0 0 .362-.92V6.853c0-.747-.606-1.353-1.353-1.353M5.5 18.991V29.01c0 .747.606 1.352 1.353 1.352h8.34c.342 0 .67-.129.92-.36l5.577-5.175c.48-.446.48-1.206 0-1.652L16.114 18a1.35 1.35 0 0 0-.92-.362H6.853c-.747 0-1.353.606-1.353 1.353m35.647-1.352h-8.34c-.342 0-.67.129-.921.36l-5.576 5.175a1.126 1.126 0 0 0 0 1.652l5.418 5.027l-1.875 1.875l-5.027-5.418a1.126 1.126 0 0 0-1.652 0L18 31.886c-.233.25-.361.579-.361.92v8.341c0 .748.605 1.353 1.352 1.353H42.5V18.991c0-.747-.606-1.352-1.353-1.352");
}

</style>

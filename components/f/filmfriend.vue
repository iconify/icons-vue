<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gehe83u6z"/><path class="emyciunrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:filmfriend" /></template>
<style>
.emyciunrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.754 23.205l-8.92-4.634a.896.896 0 0 0-1.31.795v9.268a.896.896 0 0 0 1.31.795l8.92-4.634a.896.896 0 0 0 0-1.59");
}

.gehe83u6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 9.5h23c4.415 0 8 3.585 8 8v21h-31c-4.415 0-8-3.585-8-8v-13c0-4.415 3.585-8 8-8");
}

</style>

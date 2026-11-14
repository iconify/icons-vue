<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hj-t_6n8w"/><path class="p1ed09bpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-meter" /></template>
<style>
.hj-t_6n8w {
  d: path("M5.5 9.5h13v12h-13Zm4 0a2.5 2.5 0 0 1 5 0");
}

.p1ed09bpy {
  d: path("M9 17.5a3 3 0 0 1 6 0m-3 0l1.25-1.75M12 2.5v1.75M7 4l1.5 1.5M17 4l-1.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

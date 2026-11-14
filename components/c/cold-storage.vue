<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vzbwgxc9w"/><path class="a55bxhngf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-storage" /></template>
<style>
.a55bxhngf {
  d: path("M6.25 5.25h6.5v5h-6.5ZM7 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11-.5v7m-3-5.25l6 3.5m-6 0l6-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzbwgxc9w {
  d: path("M12.2 20.5H3v-18h13v9.2");
}

</style>

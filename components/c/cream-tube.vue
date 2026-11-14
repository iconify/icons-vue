<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aqde1fbow"/><path class="r2dluxbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cream-tube" /></template>
<style>
.aqde1fbow {
  d: path("m13.061 6.197l4.242 4.242l-5.657 8.486l-7.071-7.071Z");
}

.r2dluxbql {
  d: path("M4.222 11.5L12 19.278l-1.768 1.768l-7.778-7.778Zm12.197-6.894l2.475 2.475l-2.475 2.474l-2.474-2.474ZM15.5 20q0-3.5 3-3.5t3 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j5k7_ik1y"/><path class="avvysqc5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-handle-lever" /></template>
<style>
.avvysqc5b {
  d: path("M8.5 6.5H12v11H8.5Zm3.5 3h7.5a1.5 1.5 0 0 1 0 3H12");
}

.j5k7_ik1y {
  d: path("M3 2.5h12.5v19H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

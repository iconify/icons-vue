<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obq99-byt"/><path class="dn42pvb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:award-envelope" /></template>
<style>
.dn42pvb0v {
  d: path("M3.5 13.5L12 18l8.5-4.5M12 3l1.029 2.334l2.537.257l-1.902 1.7l.54 2.493L12 8.5L9.796 9.784l.54-2.493l-1.902-1.7l2.537-.257Z");
}

.obq99-byt {
  d: path("M3 12.5h18v9H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

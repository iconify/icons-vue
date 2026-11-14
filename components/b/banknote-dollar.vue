<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="b8hztkbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:banknote-dollar" /></template>
<style>
.b8hztkbxc {
  d: path("M14.5 9.5c-.35-1.05-1.3-1.7-2.5-1.75c-1.45.05-2.4.9-2.5 2c.1 3 4.9 1.5 5 4.5c-.1 1.2-1.15 1.95-2.5 2c-1.35-.05-2.25-.7-2.5-1.75M12 6.75v1m0 8.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrcg6qhaf {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>

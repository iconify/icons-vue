<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bmn5facjv"/><path class="a206a4bym"/><path class="knz1v6b1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-counter" /></template>
<style>
.a206a4bym {
  d: path("M5.5 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.bmn5facjv {
  d: path("M2.5 2.5h19V15h-19ZM12 15v6.5m-3 0h6");
}

.knz1v6b1l {
  d: path("M7.5 10H11l3-4l2.5 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

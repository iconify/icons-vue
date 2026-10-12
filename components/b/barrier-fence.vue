<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ousix7bwx"/><path class="algnqfbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barrier-fence" /></template>
<style>
.algnqfbwr {
  d: path("m7 12l4-6.5m2 6.5l4-6.5M6 12v8.5M18 12v8.5m-14.75 0h5.5m6.5 0h5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ousix7bwx {
  width: 18.5px;
  height: 6.5px;
  x: 2.75px;
  y: 5.5px;
  rx: 1.25px;
}

</style>

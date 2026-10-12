<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qo1e4q8jy"/><path class="ojys_c1kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojys_c1kc {
  d: path("M2.75 14.25c1.55 0 1.55 1.25 3.08 1.25s1.55-1.25 3.09-1.25S10.46 15.5 12 15.5s1.54-1.25 3.08-1.25s1.55 1.25 3.09 1.25s1.53-1.25 3.08-1.25m-15 4h11.5M12 10.75V7.5m0-4.75c.95 1 1.5 1.85 1.5 2.5a1.5 1.5 0 0 1-3 0c0-.65.55-1.5 1.5-2.5");
}

.qo1e4q8jy {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 10.75px;
  rx: 2.5px;
}

</style>

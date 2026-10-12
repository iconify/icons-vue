<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t3yejqb7x"/><path class="s-htnoz9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cabinet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-htnoz9k {
  d: path("M2.75 9h18.5M12 9v10.25M10.5 6.6h3m-4 5.4v2.5m5-2.5v2.5M6 19.25v2m12-2v2");
}

.t3yejqb7x {
  width: 18.5px;
  height: 15px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>

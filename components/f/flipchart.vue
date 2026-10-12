<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lyvzlo38j"/><path class="xnc3gdmfi"/><path class="n9cj3_bbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flipchart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyvzlo38j {
  width: 18.5px;
  height: 2.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.25px;
}

.n9cj3_bbd {
  d: path("m7.25 12l2.5-2.5l2 1.5l3-3.25m-6.25 7.5l-1.75 6m8.75-6l1.75 6");
}

.xnc3gdmfi {
  d: path("M5 5.25h14q.75 0 .75.75v6q0 .75-.53 1.28l-1.44 1.44q-.53.53-1.28.53H5q-.75 0-.75-.75V6q0-.75.75-.75");
}

</style>

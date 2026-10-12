<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k0bjsebqo"/><path class="o6bxdibgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hall-pass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0bjsebqo {
  width: 13.5px;
  height: 12.5px;
  x: 5.25px;
  y: 8.75px;
  rx: 2.5px;
}

.o6bxdibgr {
  d: path("M12 8.75C9.25 7.5 9.5 3 12 3s2.75 4.5 0 5.75M8.75 15h6.5m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

</style>

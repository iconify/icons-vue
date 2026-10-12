<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gg_xxm92g"/><path class="kxqfomzvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lawyer-briefcase" /></template>
<style>
.gg_xxm92g {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxqfomzvh {
  d: path("M8.75 7.25v-1.5a2 2 0 0 1 2-2h2.5a2 2 0 0 1 2 2v1.5M12 10.75v6.5m-1.75 0h3.5M8 12h8m-8 0l-1.25 2.75h2.5Zm8 0l-1.25 2.75h2.5Z");
}

</style>

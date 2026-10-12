<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="suot8mbzd"/><path class="qwg5kl0zx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:artboard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qwg5kl0zx {
  d: path("M2.75 3.5h6m8-.75v1.5m3 3h1.5m-1.5 11h1.5m-4.5 3v-1.5");
}

.suot8mbzd {
  width: 14px;
  height: 11px;
  x: 2.75px;
  y: 7.25px;
  rx: 1.5px;
}

</style>

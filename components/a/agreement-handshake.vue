<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="em7bq-bri"/><rect class="jy6abx7ao"/><path class="nctfihblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agreement-handshake" /></template>
<style>
.em7bq-bri {
  width: 3.5px;
  height: 7.5px;
  x: 2.75px;
  y: 8.5px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jy6abx7ao {
  width: 3.5px;
  height: 7.5px;
  x: 17.75px;
  y: 8.5px;
  rx: 1px;
}

.nctfihblj {
  d: path("m6.25 9.5l3-1.25h3l2.5 1.25h3v6l-4.5 3.4a1.5 1.5 0 0 1-1.9 0l-5.1-3.4Zm6.25 0l-2.75 1.75m-.25 2.5l2.25 2m-.25-3.25l2.25 2");
}

</style>

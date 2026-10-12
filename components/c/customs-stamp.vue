<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gy1-t8ffj"/><path class="iwpq8xbzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customs-stamp" /></template>
<style>
.gy1-t8ffj {
  width: 14.5px;
  height: 9px;
  x: 4.75px;
  y: 12.25px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iwpq8xbzm {
  d: path("m10 17l1.5 1.5l3-3m2.15-12.43l.94.34q.47.17.3.64l-.52 1.41q-.17.47.3.64l.94.35q.47.17.3.64L18.4 8.5q-.17.47-.64.3l-4.7-1.72q-.47-.17-.3-.64l.51-1.41q.17-.47.64-.3l.94.35q.47.17.64-.3l.52-1.41q.17-.47.64-.3");
}

</style>

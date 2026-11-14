<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aynpw1b9r"/><path class="zanu6abbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fundraising-share" /></template>
<style>
.aynpw1b9r {
  d: path("M4.25 7.5h2.315a1.75 1.75 0 0 0 .819-.203l5.547-2.937A1.75 1.75 0 0 1 15.5 5.907v6.835a1.75 1.75 0 0 1-2.495 1.584l-5.651-2.659a1.75 1.75 0 0 0-.745-.167H4.25A1.75 1.75 0 0 1 2.5 9.75v-.5A1.75 1.75 0 0 1 4.25 7.5m.75 4l1.25 5m8.75 5c0-3 1.75-4 5.75-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zanu6abbg {
  d: path("m18.75 15.5l2 2l-2 2");
}

</style>

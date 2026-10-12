<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ann80wu5h"/><rect class="f6a4x752l"/><path class="erjoh7b_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gutter-drain" /></template>
<style>
.ann80wu5h {
  d: path("M2.75 2.75h18.5");
}

.erjoh7b_c {
  d: path("M7 5.25V8.5m5-3.25V8.5m4 0h3v8.75a3 3 0 0 1-3 3h-3.5v-3H16Zm-7.5 7c1 1.25 1.6 2.1 1.6 2.95a1.6 1.6 0 0 1-3.2 0c0-.85.6-1.7 1.6-2.95");
}

.f6a4x752l {
  width: 18.5px;
  height: 3.25px;
  x: 2.75px;
  y: 5.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

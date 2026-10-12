<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sfgk-_6av"/><path class="oa2v_dbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incubator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oa2v_dbot {
  d: path("M5.75 14.5h9.5m3-7v5m-11-4h6.5m-6.5 3h6.5M6.5 18.75v2.5m11-2.5v2.5");
}

.sfgk-_6av {
  width: 18.5px;
  height: 15.25px;
  x: 2.75px;
  y: 3.5px;
  rx: 2.5px;
}

</style>

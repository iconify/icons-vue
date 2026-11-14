<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ksm760gkm"/><path class="butimhb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electrolysis" /></template>
<style>
.butimhb0o {
  d: path("M10.75 15a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksm760gkm {
  d: path("M3.5 6v13.5a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V6M8 2.5V17m8-14.5V17M3.5 10h17");
}

</style>

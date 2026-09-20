<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgrfb-bqu"/><path class="nooweob_o"/><path class="gmrzwr9af"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:attribution-outline-thin" /></template>
<style>
.gmrzwr9af {
  d: path("M14 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nooweob_o {
  d: path("M3 10h12");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>

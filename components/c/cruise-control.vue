<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yda0a_kfi"/><path class="mp1jjnbtm"/><circle class="hvgdv64iz"/><path class="aod8jqbni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cruise-control" /></template>
<style>
.aod8jqbni {
  d: path("M13.24 11.76L15.5 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvgdv64iz {
  cx: 12px;
  cy: 13px;
  r: 1.75px;
}

.mp1jjnbtm {
  d: path("m18.25 11.5l1.5 1.5l1.5-1.5");
}

.yda0a_kfi {
  d: path("M6.52 18.48A7.75 7.75 0 1 1 19.75 13");
}

</style>

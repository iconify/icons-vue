<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yzqz0_2qw"/><path class="ljyw6db6q"/><circle class="kltucobhk"/><path class="sfz09sb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:encrypted-connection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kltucobhk {
  cx: 16px;
  cy: 18.75px;
  r: 2px;
}

.ljyw6db6q {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4m-4 3.75h2.5");
}

.sfz09sb9c {
  d: path("m17.5 17.25l3-3m-1.25 1.25l1.25 1.25");
}

.yzqz0_2qw {
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3");
}

</style>

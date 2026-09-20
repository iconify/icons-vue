<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="b266jkbmh"/><path class="m-436sbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:countdown-sale-outline-thin" /></template>
<style>
.b266jkbmh {
  d: path("M7 3v4l5 5 5 -5V3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-436sbse {
  d: path("M7 21v-4l5 -5 5 5v4");
}

.rjrs_5bsc {
  d: path("M6 3h12");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>

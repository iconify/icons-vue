<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybyzelb1a"/><path class="wyjc_m-sx"/><path class="jr8el6bas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:element-actinium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jr8el6bas {
  d: path("M7.25 20.25a9.5 3.5 120 1 1 9.5-16.5a9.5 3.5 120 1 1-9.5 16.5M12 12h.01");
}

.wyjc_m-sx {
  d: path("M16.75 20.25a9.5 3.5 60 1 1-9.5-16.5a9.5 3.5 60 1 1 9.5 16.5");
}

.ybyzelb1a {
  d: path("M2.5 12a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0");
}

</style>

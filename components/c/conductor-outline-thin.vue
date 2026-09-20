<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jy2rzibrh"/><path class="rc4z2wbgq"/><path class="aw2xgdc6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:conductor-outline-thin" /></template>
<style>
.aw2xgdc6s {
  d: path("m14 15 7 -7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jy2rzibrh {
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.rc4z2wbgq {
  d: path("M4.5 16a4.5 4.5 0 0 1 9 0");
}

</style>

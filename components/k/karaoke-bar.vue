<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-9559bdj"/><path class="ub0i8md0w"/><path class="sbh-nd56v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:karaoke-bar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-9559bdj {
  d: path("m4.138 9.475l6.75-5.559a1.75 1.75 0 0 1 2.224 0l6.75 5.559a1.75 1.75 0 0 1 .638 1.351v8.424A1.75 1.75 0 0 1 18.75 21H5.25a1.75 1.75 0 0 1-1.75-1.75v-8.424a1.75 1.75 0 0 1 .638-1.351");
}

.sbh-nd56v {
  d: path("M7.75 11.5a4.25 4.25 0 0 0 8.5 0M12 15.75v2.5");
}

.ub0i8md0w {
  d: path("M12 8za1.5 1.5 0 0 1 1.5 1.5v2A1.5 1.5 0 0 1 12 13a1.5 1.5 0 0 1-1.5-1.5v-2A1.5 1.5 0 0 1 12 8");
}

</style>

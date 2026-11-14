<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e86sqnywv"/><path class="a5s3uebmx"/><path class="fk60ovbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:highlighter" /></template>
<style>
.a5s3uebmx {
  d: path("m10.29 11.704l2.006 2.006A1.14 1.14 0 0 1 12 15.536l-.447.223a1.5 1.5 0 0 1-1.732-.281l-1.299-1.299a1.5 1.5 0 0 1-.281-1.732L8.464 12a1.14 1.14 0 0 1 1.826-.296");
}

.e86sqnywv {
  d: path("m18.452 5.017l.531.531a2.625 2.625 0 0 1 0 3.712l-3.713 3.712a2.625 2.625 0 0 1-3.712 0l-.53-.53a2.625 2.625 0 0 1 0-3.712l3.712-3.713a2.625 2.625 0 0 1 3.712 0");
}

.fk60ovbjz {
  d: path("m9.172 14.828l.53.531a.75.75 0 0 1 0 1.06a1.21 1.21 0 0 1-1.242.294l-1.047-.35a.927.927 0 0 1-.363-1.535a1.5 1.5 0 0 1 2.122 0M3 21h6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

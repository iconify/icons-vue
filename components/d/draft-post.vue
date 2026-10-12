<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f2rhuvbid"/><path class="t2mq0suwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:draft-post" /></template>
<style>
.f2rhuvbid {
  width: 14.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t2mq0suwj {
  d: path("M6.5 7.5h7m-7 3.5h7m-7 3.5h3M18.25 9a1.6 1.6 0 0 1 2.25 2.25l-6.5 6.5l-3 .75l.75-3Z");
}

</style>

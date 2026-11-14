<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w4_9v8bgh"/><path class="v6l9gj2fc"/><path class="krrs7pb-v"/><path class="henmhkbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gps-approach" /></template>
<style>
.henmhkbsf {
  d: path("M20.932 18.457za1.25 1.25 0 0 1 0 1.768l-.707.707a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l.707-.707a1.25 1.25 0 0 1 1.768 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krrs7pb-v {
  d: path("m18.104 16.689l.707.707a1 1 0 0 1 0 1.415a1 1 0 0 1-1.415 0l-.707-.707a1 1 0 0 1 0-1.415a1 1 0 0 1 1.415 0");
}

.v6l9gj2fc {
  d: path("M17.043 14.568za1.25 1.25 0 0 1 0 1.768l-.707.707a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l.707-.707a1.25 1.25 0 0 1 1.768 0");
}

.w4_9v8bgh {
  d: path("M15.422 21H3.5l5-18h5l2.572 8.416M11.25 7v3m0 3.5v3");
}

</style>

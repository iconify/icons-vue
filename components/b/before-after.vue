<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7ycsdbmm"/><path class="rx18j4bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:before-after" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rx18j4bxv {
  d: path("M5 6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.25 5c.25-1.25 1.5-1.75 3-1.75s2.75.5 3 1.75m7.911-6.191l.065.126a1.5 1.5 0 0 0 1.103.802l.14.022a.462.462 0 0 1 .254.782l-.1.101a1.5 1.5 0 0 0-.421 1.297l.022.14a.462.462 0 0 1-.666.483l-.126-.064a1.5 1.5 0 0 0-1.364 0l-.126.064a.462.462 0 0 1-.666-.483l.022-.14a1.5 1.5 0 0 0-.421-1.297l-.1-.101a.462.462 0 0 1 .254-.782l.14-.022a1.5 1.5 0 0 0 1.103-.802l.065-.126a.462.462 0 0 1 .822 0");
}

.x7ycsdbmm {
  d: path("M5.125 3h3.25A2.625 2.625 0 0 1 11 5.625v3.25A2.625 2.625 0 0 1 8.375 11.5h-3.25A2.625 2.625 0 0 1 2.5 8.875v-3.25A2.625 2.625 0 0 1 5.125 3m10.5 0h3.25A2.625 2.625 0 0 1 21.5 5.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 13 8.875v-3.25A2.625 2.625 0 0 1 15.625 3M6.75 17.5h10.5m-2.75-2.75l2.75 2.75l-2.75 2.75");
}

</style>

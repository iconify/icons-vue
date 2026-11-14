<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ej4mrob6j"/><path class="e5q8326mg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:employee-of-the-month" /></template>
<style>
.e5q8326mg {
  d: path("M9.75 12.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-2 9c0-2.5 2-4 4.25-4s4.25 1.5 4.25 4");
}

.ej4mrob6j {
  d: path("M7.125 7.5h9.75a2.625 2.625 0 0 1 2.625 2.625v8.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875v-8.75A2.625 2.625 0 0 1 7.125 7.5m5.286-4.191l.065.126a1.5 1.5 0 0 0 1.103.802l.14.022a.462.462 0 0 1 .254.782l-.1.101a1.5 1.5 0 0 0-.421 1.297l.022.14a.462.462 0 0 1-.666.483l-.126-.064a1.5 1.5 0 0 0-1.364 0l-.126.064a.462.462 0 0 1-.666-.483l.022-.14a1.5 1.5 0 0 0-.421-1.297l-.1-.101a.462.462 0 0 1 .254-.782l.14-.022a1.5 1.5 0 0 0 1.103-.802l.065-.126a.462.462 0 0 1 .822 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

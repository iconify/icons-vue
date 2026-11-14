<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mp42_8wzt"/><path class="pr-xiqbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dialysis-machine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mp42_8wzt {
  d: path("M13.017 14.718c-.707-.97-1.517-1.608-1.517-3.218c0-2 1.5-2.5 2.25-4C14.75 5.25 13.5 3 11 3c-5 0-7.5 4.5-7.5 8.5c0 4.5 3 8 7 8c.676 0 1.251-.102 1.724-.282M11.5 11.5h3.3m4.7 3.652A3 3 0 0 1 18 20.75m-1.5-.402A3 3 0 0 1 18 14.75");
}

.pr-xiqbis {
  d: path("M16.75 13.5L18 14.75L16.75 16m2.5 3.5L18 20.75L19.25 22");
}

</style>

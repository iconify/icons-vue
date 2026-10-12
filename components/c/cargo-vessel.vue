<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc1466b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cargo-vessel" /></template>
<style>
.oc1466b-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5h18.5l-1.75 3.9a1.75 1.75 0 0 1-1.62 1.1H6.12a1.75 1.75 0 0 1-1.62-1.1Zm13 0v-6a1 1 0 0 1 1-1h2.5a1 1 0 0 1 1 1v6ZM6 12.5V3.25l4.5 3.25m1 6V3.25m-8.75 18c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d83bizbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cohort" /></template>
<style>
.d83bizbtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6A2.25 2.25 0 1 0 7 6a2.25 2.25 0 1 0-4.5 0Zm7.25 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM17 6a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 17 6ZM2.5 15.5v2h19v-2M2.5 13c0-1.75 1-2.75 2.25-2.75S7 11.25 7 13m2.75 0c0-1.75 1-2.75 2.25-2.75s2.25 1 2.25 2.75M17 13c0-1.75 1-2.75 2.25-2.75s2.25 1 2.25 2.75M12 17.5V21");
}

</style>

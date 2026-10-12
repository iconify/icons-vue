<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi0ctjb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hydro-dam-sharp" /></template>
<style>
.wi0ctjb-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.25h2l.34.94l5.82 16.12l.34.94H10v-18zM2.75 8l1.3-1.5L5.35 8l1.3 1.5L7.95 8m-5.2 4.5l1.3-1.5l1.3 1.5l1.3 1.5l1.3-1.5M2.75 17l1.3-1.5l1.3 1.5l1.3 1.5l1.3-1.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4ccj4voc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fundraising-thermometer" /></template>
<style>
.r4ccj4voc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 13.25v-8.5a2.5 2.5 0 0 1 5 0v8.5a4.5 4.5 0 1 1-5 0Zm2.5-4.75v8.25M16 8.5h2.5");
}

</style>

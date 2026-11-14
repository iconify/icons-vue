<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd9-0il0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canoe-slalom" /></template>
<style>
.fd9-0il0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5V12m15-9.5V12m-17 2.5c3.5 6 15.5 6 19 0C16 16 8 16 2.5 14.5M6.552 3.423L7 3.625a1.234 1.234 0 0 1 0 2.25l-.448.202A1.455 1.455 0 0 1 4.5 4.75a1.455 1.455 0 0 1 2.052-1.327m10.896 0L17 3.625a1.234 1.234 0 0 0 0 2.25l.448.202A1.455 1.455 0 0 0 19.5 4.75a1.455 1.455 0 0 0-2.052-1.327");
}

</style>

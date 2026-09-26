<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko1__nbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bold-two-tone" /></template>
<style>
.ko1__nbwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 21V3H13C15.2091 3 17 4.7909 17 7C17 9.2091 15.2091 11 13 11M5 11H14C16.7614 11 19 13.2386 19 16C19 18.7614 16.7614 21 14 21H5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpw2dcbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:garage-open" /></template>
<style>
.mpw2dcbmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 22H3C2.4477 22 2 21.552 2 21V7L11.544 2.11C11.8303 1.963 12.1697 1.963 12.456 2.11L22 7V21C22 21.552 21.5523 22 21 22H18M18 22V12C18 11.448 17.5523 11 17 11H7C6.4477 11 6 11.448 6 12V22M18 22H6M22 7H2");
}

</style>

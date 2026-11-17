<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-srupb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-pull-sharp-two-tone" /></template>
<style>
.i-srupb8n {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2V23M13.293 5.2929L10 2L6.707 5.2929M10 10C10 13.3 12.82 15.8056 17 17L17.725 17.2072");
}

</style>

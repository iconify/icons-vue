<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omt9jab7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-play-sharp" /></template>
<style>
.omt9jab7v {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3H20M3 7H21V21H3V7ZM9.5 10.38L14.813 14L9.5 17.62V10.38Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp6hk7b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-scan" /></template>
<style>
.wp6hk7b1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H6C4.3431 3 3 4.3431 3 6V18C3 19.6569 4.3431 21 6 21H13M8 3V21M3 12H13M3 7.5H8M3 16.5H8M13 2V22M17 3V10M17 21V14M21 20V18M21 14V10M21 6V4");
}

</style>

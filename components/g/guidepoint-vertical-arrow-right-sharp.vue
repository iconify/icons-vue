<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oua700z5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guidepoint-vertical-arrow-right-sharp" /></template>
<style>
.oua700z5k {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8C5.343 8 4 6.66 4 5C4 3.34 5.343 2 7 2C8.657 2 10 3.34 10 5C10 6.66 8.657 8 7 8ZM7 8V16M7 16C8.657 16 10 17.34 10 19C10 20.66 8.657 22 7 22C5.343 22 4 20.66 4 19C4 17.34 5.343 16 7 16ZM14 7.51L20 12L14 16.49V7.51Z");
}

</style>

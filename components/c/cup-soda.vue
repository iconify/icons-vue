<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0p9wubrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cup-soda" /></template>
<style>
.s0p9wubrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10H18M6 10C5.4477 10 5 9.55 5 9C5 8.78 5.0702 8.57 5.2 8.4L6.4 6.8C6.7777 6.3 7.3705 6 8 6H16C16.6295 6 17.2223 6.3 17.6 6.8L18.8 8.4C18.9298 8.57 19 8.78 19 9C19 9.55 18.5523 10 18 10M6 10L8.6213 20.49C8.8439 21.38 9.6438 22 10.5616 22H13.4384C14.3562 22 15.1561 21.38 15.3787 20.49L18 10M11 6L12.7236 2.55C12.893 2.21 13.2393 2 13.618 2H16");
}

</style>

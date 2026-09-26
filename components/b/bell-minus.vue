<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzk0y1b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-minus" /></template>
<style>
.tzk0y1b8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5801 12C16.1706 13.7121 17 14.356 17 15C17 15.5523 16.5523 16 16 16L4 16C3.4477 16 3 15.5523 3 15C3 14 5 13 5 8C5 5.2386 7.2386 3 10 3C10.7111 3 11.3875 3.1484 12 3.416M8.2679 20C8.6252 20.6188 9.2855 21 10 21C10.7145 21 11.3748 20.6188 11.7321 20M16 5L22 5");
}

</style>

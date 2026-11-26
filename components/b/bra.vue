<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvzs6wb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bra" /></template>
<style>
.qvzs6wb8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.9909 11.0068C2.7372 11.9515 2 13.4302 2 15C2 17.7614 4.2386 20 7 20C9.7614 20 12 17.7614 12 15M3.9909 11.0068L12 15M3.9909 11.0068V4M12 15C12 17.7614 14.2386 20 17 20C19.7614 20 22 17.7614 22 15C22 13.4302 21.2628 11.9515 20.0091 11.0068M12 15L20.0091 11.0068M20.0091 11.0068V4");
}

</style>

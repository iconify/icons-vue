<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0n7lbb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heart-arrow" /></template>
<style>
.n0n7lbb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 20.4l-4.2-4.2c-.9-.87-1.8-1.92-1.8-3.3c0-1.83 1.47-3.3 3.3-3.3c1.05 0 1.8.3 2.7 1.2c.9-.9 1.65-1.2 2.7-1.2c1.83 0 3.3 1.47 3.3 3.3c0 1.38-.9 2.43-1.8 3.3ZM18 8.7l-2.1-2.1c-.45-.44-.9-.96-.9-1.65c0-.91.74-1.65 1.65-1.65c.53 0 .9.15 1.35.6c.45-.45.82-.6 1.35-.6c.91 0 1.65.74 1.65 1.65c0 .69-.45 1.21-.9 1.65Z");
}

</style>

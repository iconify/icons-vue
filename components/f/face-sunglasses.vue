<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg6zexbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-sunglasses" /></template>
<style>
.lg6zexbxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.3397 7C5.1261 3.906 8.4273 2 12 2C15.5727 2 18.8739 3.906 20.6603 7M21.9035 10.6139C21.9677 11.0731 22 11.5363 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 11.5363 2.0323 11.0731 2.0965 10.6139M2 8C2 7.4477 2.4477 7 3 7L9 7C9.5523 7 10 7.4477 10 8L10 10C10 11.1046 9.1046 12 8 12L4 12C2.8954 12 2 11.1046 2 10ZM14 8C14 7.4477 14.4477 7 15 7L21 7C21.5523 7 22 7.4477 22 8L22 10C22 11.1046 21.1046 12 20 12L16 12C14.8954 12 14 11.1046 14 10ZM10 8H14M9 16C10 17 11 17.5 12 17.5C13 17.5 14 17 15 16");
}

</style>

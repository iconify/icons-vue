<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q12mu5ejy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layout-bento-sharp" /></template>
<style>
.q12mu5ejy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L3 10L12 10L12 3L3 3ZM16 3L16 10L21 10L21 3L16 3ZM3 14L3 21L8 21L8 14L3 14ZM12 14L12 21L21 21L21 14L12 14Z");
}

</style>

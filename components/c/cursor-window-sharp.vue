<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfvuw-z8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-window-sharp" /></template>
<style>
.qfvuw-z8q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 20L3 20L3 3L20 3L20 10M6 7L10 7M10.5489 10.528L14.1426 21L16.6527 16.4663L21 14.3L10.5489 10.528Z");
}

</style>

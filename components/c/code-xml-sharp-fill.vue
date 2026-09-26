<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sro2fub8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-xml-sharp-fill" /></template>
<style>
.sro2fub8t {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.3002 6.6247L2 12L6.3002 17.3753M17.6998 6.6247L22 12L17.6998 17.3753M9.7928 19.7253L14.2072 4.2747");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-sdc7buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-vertical-sharp" /></template>
<style>
.e-sdc7buc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.9999 1.9999L12 8L7.0001 1.9999L16.9999 1.9999ZM16.9999 22.0001L12 16.0001L7.0001 22.0001L16.9999 22.0001ZM23 12L19 12M17 12L13 12M11 12L7 12M5 12L1 12");
}

</style>

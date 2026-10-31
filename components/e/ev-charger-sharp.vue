<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if2r8_b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-sharp" /></template>
<style>
.if2r8_b7f {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 2L14 2L14 22L2 22ZM14 22L23 22M14 17L20 17L20 10M18 6L22 6L22 10L18 10ZM22 6L22 3M18 6L18 3M9.3 7.6L6 12L10 12L6.7 16.4");
}

</style>

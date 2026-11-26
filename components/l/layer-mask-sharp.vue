<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6etrqzzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-mask-sharp" /></template>
<style>
.q6etrqzzk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 20L2 20ZM12 8C14.2091 8 16 9.7909 16 12C16 14.2091 14.2091 16 12 16C9.7909 16 8 14.2091 8 12C8 9.7909 9.7909 8 12 8Z");
}

</style>

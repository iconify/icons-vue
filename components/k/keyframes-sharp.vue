<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-gxsgb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyframes-sharp" /></template>
<style>
.b-gxsgb_c {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.4343 3L15.8685 12L9.4343 21L3 12L9.4343 3ZM14.8048 2.5482L21 12L14.8048 21.4518");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw1s7f9mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:log-in-sharp" /></template>
<style>
.uw1s7f9mw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 4L21 4L21 20L14 20M13.6493 12L2 12M7.7469 6.204L13.8907 12L7.7469 17.796");
}

</style>

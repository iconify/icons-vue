<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la6_f2vsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-check" /></template>
<style>
.la6_f2vsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h4a2 2 0 0 1 2 2v12c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V6a2 2 0 0 1 2-2zm-3 6l2 2l4-4");
}

</style>

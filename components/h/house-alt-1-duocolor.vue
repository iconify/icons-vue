<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n48-j5uix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-duocolor" /></template>
<style>
.n48-j5uix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 17v2a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-8.092a2 2 0 0 0-.683-1.506l-6-5.25a2 2 0 0 0-2.634 0l-6 5.25A2 2 0 0 0 4 10.908V19a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-2a2 2 0 1 1 4 0");
}

</style>

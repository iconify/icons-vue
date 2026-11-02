<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9axxpspf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cupcake-sharp" /></template>
<style>
.s9axxpspf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14h14l-1 5c-.24 1.18-.9 2-2 2H8c-1.1 0-1.76-.82-2-2zm5 0v7m4-7v7m5-7c2.998-1.706 2.356-6.202-1-7c-.115-2.5-2.74-4.075-5-3a5 5 0 0 0-8 4c-2.567 1.176-2.567 4.824 0 6");
}

</style>

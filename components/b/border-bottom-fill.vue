<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr6iwh0po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:border-bottom-fill" /></template>
<style>
.vr6iwh0po {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 18C21 19.6569 19.6569 21 18 21H6C4.34315 21 3 19.6569 3 18M3 6C3 4.34315 4.34315 3 6 3M10.5 3H13.5M18 3C19.6569 3 21 4.34315 21 6M21 10.5V13.5M3 13.5V10.5");
}

</style>

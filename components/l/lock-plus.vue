<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewq6pku5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-plus" /></template>
<style>
.ewq6pku5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 10V6.5C7.5 4.01472 9.51472 2 12 2C14.4853 2 16.5 4.01472 16.5 6.5V10M4 13V19C4 20.6569 5.34315 22 7 22H17C18.6569 22 20 20.6569 20 19V13C20 11.3431 18.6569 10 17 10H7C5.34315 10 4 11.3431 4 13ZM12 14V18M10 16H14");
}

</style>

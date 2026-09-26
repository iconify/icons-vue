<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdd7vy8ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-up-dashed-panel-fill" /></template>
<style>
.wdd7vy8ix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6C3 4.34315 4.34315 3 6 3M10.5 3H13.5M21 7V6.00026C21 4.34341 19.6569 3 18 3M7 21H6C4.34315 21 3 19.6569 3 18M3 10.5V13.5M15.5 11V21M10 16L15.1314 10.4021C15.3296 10.1859 15.6704 10.1859 15.8686 10.4021L21 16");
}

</style>

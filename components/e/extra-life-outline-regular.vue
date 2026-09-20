<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpuj6eb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:extra-life-outline-regular" /></template>
<style>
.hpuj6eb7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20c-4 -3 -9 -7 -7 -11.5 1.5 -3 5 -2 7 1 2 -3 5.5 -4 7 -1C21 13 16 17 12 20");
}

</style>

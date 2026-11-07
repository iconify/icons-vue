<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztv-8b_2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-off" /></template>
<style>
.ztv-8b_2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.432 6.432a8 8 0 1 0 11.137 11.137M20 13a8 8 0 0 0-8-8M3 6l2-2m13-1l3 3M3 2l19 19");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuf0a7bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-through-line-sharp-two-tone" /></template>
<style>
.vuf0a7bbw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12L21 12M16.7071 7.7071L21 12L16.7071 16.2929M12 2L12 9M12 15L12 22");
}

</style>

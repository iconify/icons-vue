<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-bx2rzyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-right-line-sharp-duotone" /></template>
<style>
.b-bx2rzyd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 19L12 19C9.2386 19 7 16.7614 7 14C7 11.2386 9.2386 9 12 9L20.6247 9M15.7261 4.7809L21 9L15.6247 13.3002M3 3L3 21");
}

</style>

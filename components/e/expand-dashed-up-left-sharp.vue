<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm498ybdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left-sharp" /></template>
<style>
.gm498ybdo {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 14L18 3M21.2929 6.2929L18 3L14.7071 6.2929M14 18L3 18M6.2929 14.7071L3 18L6.2929 21.2929M3 12L3 8.6667M3 6.6667L3 3L6.6667 3M8.6667 3L12 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1mhh7bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-left-sharp-fill" /></template>
<style>
.r1mhh7bie {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.8907 4L22 4L22 20L11.8907 20M2.2414 12L13.8907 12M8.1438 6.204L2 12L8.1438 17.796");
}

</style>

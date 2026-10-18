<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7r6p9dzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-nested-sharp-fill" /></template>
<style>
.c7r6p9dzq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L5 4.5L3 6ZM5 10.5L7 12L5 13.5ZM7 18L9 19.5L7 21ZM8 4.5L22 4.5M10 12L22 12M12 19.5L22 19.5");
}

</style>

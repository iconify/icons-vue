<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zpv4lqb3x"/><path class="r8-w26x5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-heart" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r8-w26x5q {
  d: path("M12 8.6028L12.4521 11.5685M15.9543 8L16.4064 10.9657");
}

.zpv4lqb3x {
  d: path("M12 21C7.4376 17.1033 2 13.75 2 8.75C2 5.5743 4.6862 3 8 3C9.5 3 10.8426 3.5459 12 4.5C13.1574 3.5459 14.5 3 16 3C19.3138 3 22 5.5743 22 8.75C22 13.75 16.5624 17.1033 12 21Z");
}

</style>

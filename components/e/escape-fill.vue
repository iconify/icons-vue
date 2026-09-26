<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nin0wu0rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:escape-fill" /></template>
<style>
.nin0wu0rp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.4412 4.0174C12.6272 4.0058 12.8136 4 13 4C17.9706 4 22 8.0294 22 13C22 17.9706 17.9706 22 13 22C8.0294 22 4 17.9706 4 13C4 12.8136 4.0058 12.6272 4.0174 12.4412M13 13L3.2 3.2M2 9L2 2.5C2 2.2239 2.2239 2 2.5 2L9 2");
}

</style>

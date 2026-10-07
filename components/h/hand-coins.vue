<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w57-5wyrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-coins" /></template>
<style>
.w57-5wyrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 4.5C21 5.8807 19.8807 7 18.5 7C17.1193 7 16 5.8807 16 4.5C16 3.1193 17.1193 2 18.5 2C19.8807 2 21 3.1193 21 4.5ZM12 5.5C12 6.8807 10.8807 8 9.5 8C8.1193 8 7 6.8807 7 5.5C7 4.1193 8.1193 3 9.5 3C10.8807 3 12 4.1193 12 5.5ZM3 14L3 22M11 14.5C11 13.6716 10.3284 13 9.5 13L7 13C6.5 13 6.1 13.2 5.8 13.5L3 16.3M3 21L4.4142 19.5858C4.7892 19.2108 5.2985 19 5.8284 19L10.5 19C11.5 19 12.4 18.6 13 18L17 14C17.7811 13.219 17.7811 11.9511 17 11.17C16.219 10.389 14.9511 10.389 14.17 11.17L11.17 14.17");
}

</style>

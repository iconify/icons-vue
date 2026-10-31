<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd8irlgrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caravan" /></template>
<style>
.bd8irlgrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 18L4 18C2.8954 18 2 17.1046 2 16L2 6C2 4.8954 2.8954 4 4 4L15 4C17.2091 4 19 5.7909 19 8L19 16C19 17.1046 18.1046 18 17 18L10 18M10 18L10 9C10 8.4477 10.4477 8 11 8L14 8C14.5523 8 15 8.4477 15 9L15 18M2 8L4.5 8C5.3284 8 6 8.6716 6 9.5L6 10.5C6 11.3284 5.3284 12 4.5 12L2 12M10 18C10 19.1046 9.1046 20 8 20C6.8954 20 6 19.1046 6 18C6 16.8954 6.8954 16 8 16C9.1046 16 10 16.8954 10 18ZM19 14L22 14");
}

</style>

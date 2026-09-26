<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lids929mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bar-stacked" /></template>
<style>
.lids929mp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21M8 5L15 5C15.5523 5 16 5.4477 16 6L16 8C16 8.5523 15.5523 9 15 9L8 9C7.4477 9 7 8.5523 7 8L7 6C7 5.4477 7.4477 5 8 5ZM8 13L18 13C18.5523 13 19 13.4477 19 14L19 16C19 16.5523 18.5523 17 18 17L8 17C7.4477 17 7 16.5523 7 16L7 14C7 13.4477 7.4477 13 8 13ZM12 5L12 9M14 13L14 17");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w926g388u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-lock" /></template>
<style>
.w926g388u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 2H8C5.79086 2 4 3.79086 4 6V18C4 20.2091 5.79086 22 8 22H9M14 2L20 8V10M14 2V5C14 6.65685 15.3431 8 17 8H20M14 18L19 18C19.5523 18 20 18.4477 20 19L20 21C20 21.5523 19.5523 22 19 22L14 22C13.4477 22 13 21.5523 13 21L13 19C13 18.4477 13.4477 18 14 18ZM14.5 18L14.5 16C14.5 14.8954 15.3954 14 16.5 14C17.6046 14 18.5 14.8954 18.5 16L18.5 18");
}

</style>

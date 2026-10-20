<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c270ezjme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layout-columns" /></template>
<style>
.c270ezjme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5L5 5C5.5523 5 6 5.4477 6 6L6 18C6 18.5523 5.5523 19 5 19L3 19C2.4477 19 2 18.5523 2 18L2 6C2 5.4477 2.4477 5 3 5ZM11 5L13 5C13.5523 5 14 5.4477 14 6L14 18C14 18.5523 13.5523 19 13 19L11 19C10.4477 19 10 18.5523 10 18L10 6C10 5.4477 10.4477 5 11 5ZM19 5L21 5C21.5523 5 22 5.4477 22 6L22 18C22 18.5523 21.5523 19 21 19L19 19C18.4477 19 18 18.5523 18 18L18 6C18 5.4477 18.4477 5 19 5Z");
}

</style>

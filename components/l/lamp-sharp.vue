<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqli40b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-sharp" /></template>
<style>
.cqli40b-n {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 10V11C14 12.6 17 13 17 15.5C17 18.5 15 19.6 14.5 22M10 10V11C10 12.6 7 13 7 15.5C7 18.5 9 19.6 9.5 22M3 22H21M8 2H16L20 10H4L8 2Z");
}

</style>

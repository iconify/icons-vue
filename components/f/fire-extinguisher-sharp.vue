<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ije1tbb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fire-extinguisher-sharp" /></template>
<style>
.ije1tbb_g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11C8 8.7909 9.7909 7 12 7C14.2091 7 16 8.7909 16 11L16 21L8 21L8 11ZM14 5C14 6.1046 13.1046 7 12 7C10.8954 7 10 6.1046 10 5C10 3.8954 10.8954 3 12 3C13.1046 3 14 3.8954 14 5ZM8 16L16 16M14 5L18 5M18 5L20.2929 2.7071M18 5L20.2929 7.2929M10 5C6.6863 5 4 7.6863 4 11L4 21M8 16L4 16");
}

</style>

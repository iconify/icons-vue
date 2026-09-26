<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm97-6bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-single" /></template>
<style>
.rm97-6bto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11L18 11C19.1046 11 20 11.8954 20 13L20 18C20 19.1046 19.1046 20 18 20L6 20C4.8954 20 4 19.1046 4 18L4 13C4 11.8954 4.8954 11 6 11ZM7 11L7 6C7 4.8954 7.8954 4 9 4L15 4C16.1046 4 17 4.8954 17 6L17 11M4 15L20 15");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oou97lt3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brackets-duotone" /></template>
<style>
.oou97lt3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 2L6 2C4.8954 2 4 2.8954 4 4L4 20C4 21.1046 4.8954 22 6 22L8 22M16 2L18 2C19.1046 2 20 2.8954 20 4L20 20C20 21.1046 19.1046 22 18 22L16 22");
}

</style>

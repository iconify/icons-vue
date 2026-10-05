<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iahggzyle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house" /></template>
<style>
.iahggzyle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 10.8473L10.7072 3.4703C11.4532 2.8383 12.5468 2.8383 13.2928 3.4703L22 10.8473M4 9.1528L4 19C4 20.1046 4.8954 21 6 21L18 21C19.1046 21 20 20.1046 20 19L20 9.1528M9 21L9 18C9 16.3431 10.3431 15 12 15C13.6569 15 15 16.3431 15 18L15 21");
}

</style>

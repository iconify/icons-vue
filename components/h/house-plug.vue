<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b290b_bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-plug" /></template>
<style>
.b290b_bfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 10.8473L10.7072 3.4703C11.4532 2.8383 12.5468 2.8383 13.2928 3.4703L22 10.8473M4 9.1528L4 19C4 20.1046 4.8954 21 6 21L18 21C19.1046 21 20 20.1046 20 19L20 9.1528M10 10L10 12M14 10L14 12M9 12L15 12C15.5523 12 16 12.4477 16 13C16 15.2091 14.2091 17 12 17C9.7909 17 8 15.2091 8 13C8 12.4477 8.4477 12 9 12ZM12 17L12 21");
}

</style>

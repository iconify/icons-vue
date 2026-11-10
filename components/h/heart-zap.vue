<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6g11fbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-zap" /></template>
<style>
.y6g11fbhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 3.34C13.2837 3.6 12.6156 3.99 12 4.5C10.8426 3.55 9.5 3 8 3C4.6862 3 2 5.57 2 8.75C2 13.75 7.4376 17.1 12 21C15.1446 18.31 18.705 15.89 20.6141 13M21 3L18 6H22L19 9");
}

</style>

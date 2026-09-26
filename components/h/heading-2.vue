<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgp3vi4ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-2" /></template>
<style>
.zgp3vi4ep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4V20M11 4V20M2 12H11M17 15C17 13.8954 17.8954 13 19 13C20.1046 13 21 13.8954 21 15C21 15.6037 20.7273 16.1751 20.258 16.5548L17 20H22");
}

</style>

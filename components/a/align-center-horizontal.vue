<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr7pzjbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-horizontal" /></template>
<style>
.rr7pzjbjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12H4M10 12H14M20 12H22M6 8H8C9.1046 8 10 8.8954 10 10V14C10 15.1046 9.1046 16 8 16H6C4.8954 16 4 15.1046 4 14V10C4 8.8954 4.8954 8 6 8ZM16 4H18C19.1045 4 20 4.8954 20 6V18C20 19.1046 19.1046 20 18 20H16C14.8955 20 14 19.1046 14 18V6C14 4.8954 14.8954 4 16 4Z");
}

</style>

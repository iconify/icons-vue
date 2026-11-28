<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fszfzjonf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-closed" /></template>
<style>
.fszfzjonf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 8C4.3607 11.1476 8.0655 13 12 13C15.9345 13 19.6393 11.1476 22 8M19.3473 10.6127L21.3142 13.3199M14.5989 12.7268L15.2946 15.9999M9.4011 12.7268L8.7054 16M4.6527 10.6127L2.6858 13.3199");
}

</style>

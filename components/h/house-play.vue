<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gim9n_bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-play" /></template>
<style>
.gim9n_bfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 10.85L20 9.15L13.2928 3.47C12.5468 2.84 11.4532 2.84 10.7072 3.47L4 9.15L2 10.85M4 9.15V19C4 20.1 4.8954 21 6 21H18C19.1046 21 20 20.1 20 19V9.15M9.5 10.9C9.5 10.19 10.2327 9.76 10.7976 10.14L15.3007 13.12C15.5664 13.29 15.5664 13.7 15.3007 13.88L10.7976 16.86C10.2327 17.24 9.5 16.81 9.5 16.1V10.9Z");
}

</style>

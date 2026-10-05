<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmc-vpewv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-chimney-sharp" /></template>
<style>
.gmc-vpewv {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.6141 11.0785L2 10.7782L12 2.9963L22 10.7782L22.3859 11.0785M4 9.2218L4 21L20 21L20 9.2218M16 6.1091L16 3L20 3L20 9.2218M9 21L9 18C9 16.3431 10.3431 15 12 15C13.6569 15 15 16.3431 15 18L15 21");
}

</style>

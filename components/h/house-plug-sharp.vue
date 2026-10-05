<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmxgmgnxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-plug-sharp" /></template>
<style>
.dmxgmgnxo {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.6141 11.0785L2 10.7782L12 2.9963L22 10.7782L22.3859 11.0785M4 9.2218L4 21L20 21L20 9.2218M10 9L10 12M14 9L14 12M8 12L16 12L16 13C16 15.2091 14.2091 17 12 17C9.7909 17 8 15.2091 8 13ZM12 17L12 21");
}

</style>

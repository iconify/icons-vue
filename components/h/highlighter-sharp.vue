<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvxg7_qbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:highlighter-sharp" /></template>
<style>
.bvxg7_qbk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.782 18.6996L6.5517 21L4.5 21C3.8975 21 3.3535 20.6395 3.1187 20.0847C2.8838 19.5299 3.0037 18.8884 3.4231 18.4559L5.7509 16.0548M5.069 15.3424L9.0341 19.4322L9.3703 19.0854C10.3511 18.0738 11.3333 17.1464 12.7204 17.1464L13.3561 17.1464L21 6.0894L18.0032 3L7.285 10.8844L7.285 11.5401C7.285 12.9708 6.386 13.9839 5.4052 14.9956Z");
}

</style>

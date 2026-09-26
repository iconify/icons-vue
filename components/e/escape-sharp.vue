<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c14fq_mes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:escape-sharp" /></template>
<style>
.c14fq_mes {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5032 4.0757L12.4412 4.0174C12.6272 4.0058 12.8136 4 13 4C17.9706 4 22 8.0294 22 13C22 17.9706 17.9706 22 13 22C8.0294 22 4 17.9706 4 13C4 12.8136 4.0058 12.6272 4.0174 12.4412L4.0757 11.5032M13 13L2.9071 2.9071M2 10L2 2L10 2");
}

</style>

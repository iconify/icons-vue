<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd08v7b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-off-sharp" /></template>
<style>
.zd08v7b-p {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14L4 4M6.6569 2L7.6569 2L20 2L20 5M10 18L2 18L2 14L10 14M22 17.3431L22 16.3431L22 10L15.6569 10L14.6569 10M13 13L13 22L22 22M1.7071 1.7071L22.2929 22.2929");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgnf816ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-open-text-sharp" /></template>
<style>
.wgnf816ww {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L8 4C10.2091 4 12 5.7909 12 8C12 5.7909 13.7909 4 16 4L22 4L22 17L15 17C13.3431 17 12 18.3431 12 20C12 18.3431 10.6569 17 9 17L2 17L2 4ZM12 8L12 20M5 9L9 9M5 13L9 13M15 9L19 9M15 13L19 13");
}

</style>

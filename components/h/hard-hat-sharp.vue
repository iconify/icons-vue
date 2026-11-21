<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbu6s3yyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-hat-sharp" /></template>
<style>
.gbu6s3yyu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 17L2 17L2 21L22 21L22 17L20 17M4 17L4 13C4 9.2723 6.5495 6.1401 10 5.252M4 17L10 17M20 17L20 13C20 9.2723 17.4505 6.1401 14 5.252M20 17L14 17M10 17L14 17M10 17L10 5.252M14 17L14 5.252M10 5.252L10 3L14 3L14 5.252");
}

</style>

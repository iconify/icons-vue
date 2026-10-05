<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5lyn5btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-up-2-sharp-fill" /></template>
<style>
.x5lyn5btw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 1L7 2L7 12.2604L7 12.9144M12.2939 7.8062L12 8.1053L7 13.1934L2 8.1053L1.7061 7.8062M17 23L17 22L17 11.7396L17 11.0856M11.7061 16.1938L12 15.8947L17 10.8066L22 15.8947L22.2939 16.1938");
}

</style>

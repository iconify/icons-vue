<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bfakpnrfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:globe-simple-thin" /></template>
<style>
.bfakpnrfm {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m91.9 96h-48c-1.15-45.55-21.74-74.52-33.48-87.4a92.14 92.14 0 0 1 81.49 87.4ZM128 218.61c-8.32-8-34.57-37.13-35.93-86.61h71.86c-1.36 49.48-27.61 78.61-35.93 86.61M92.07 124c1.36-49.48 27.61-78.61 35.93-86.61c8.32 8 34.57 37.13 35.93 86.61Zm25.47-87.4C105.8 49.48 85.21 78.45 84.06 124h-48a92.14 92.14 0 0 1 81.48-87.4M36.09 132h48c1.15 45.55 21.74 74.52 33.48 87.4A92.14 92.14 0 0 1 36.09 132m102.37 87.4c11.74-12.88 32.33-41.85 33.48-87.4h48a92.14 92.14 0 0 1-81.48 87.4");
}

</style>

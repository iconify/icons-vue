<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="li3d9-fqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flag-banner-fold-thin" /></template>
<style>
.li3d9-fqu {
  fill: currentColor;
  d: path("M235.36 45.83A4 4 0 0 0 232 44h-80a4 4 0 0 0-3.64 2.34L138.52 68H28a4 4 0 0 0-3 6.69L62.59 116L25 157.31a4 4 0 0 0 3 6.69h73.09a4 4 0 0 0 3.64-2.35l9.85-21.65h71.21l-37.43 82.34a4 4 0 0 0 2 5.3a4.1 4.1 0 0 0 1.64.36a4 4 0 0 0 3.64-2.35l80-176a4 4 0 0 0-.28-3.82M98.52 156H37l34-37.31a4 4 0 0 0 0-5.38L37 76h97.84Zm90.9-24h-71.21l36.37-80h71.21Z");
}

</style>

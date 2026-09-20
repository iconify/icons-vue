<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wh924wb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:feather-light" /></template>
<style>
.wh924wb2o {
  fill: currentColor;
  d: path("M238 80a62 62 0 0 0-105.82-43.86L62.1 105.41a13.94 13.94 0 0 0-4.1 9.9v74.21l-30.24 30.24a6 6 0 1 0 8.48 8.48L66.48 198h74.21a13.94 13.94 0 0 0 9.9-4.1l68.83-69.63l.39-.4A61.6 61.6 0 0 0 238 80m-97.36-35.36a50 50 0 0 1 72 69.36h-62.16l37.76-37.76a6 6 0 0 0-8.48-8.48l-48 48L118 129.52V67ZM70 115.31a2 2 0 0 1 .56-1.39l35.44-35v62.63l-36 36Zm72.09 70.11a2 2 0 0 1-1.4.58H78.48l37.76-37.75L138.48 126h62.35Z");
}

</style>

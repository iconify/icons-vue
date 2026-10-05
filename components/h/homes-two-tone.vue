<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="du9vs7_0d"/><path class="wxx17zt9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:homes-two-tone" /></template>
<style>
.du9vs7_0d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.0605 7.71097C13.1795 6.76301 14.8205 6.76301 15.9395 7.71097L20.9395 11.9473C21.6123 12.5173 22 13.3547 22 14.2364V19C22 20.6569 20.6569 22 19 22H9C7.34312 22 6 20.6569 6 19V14.2364C6.00002 13.3547 6.38774 12.5173 7.06055 11.9473L12.0605 7.71097Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wxx17zt9x {
  d: path("M7 19L7 14.2362C7 13.6483 7.2586 13.0902 7.7072 12.7102L12.7072 8.474C13.4532 7.842 14.5468 7.842 15.2928 8.474L20.2928 12.7102C20.7414 13.0902 21 13.6483 21 14.2362L21 19C21 20.1046 20.1046 21 19 21L9 21C7.8954 21 7 20.1046 7 19ZM3.1715 12.8116C3.0613 12.5636 3 12.289 3 12L3 7.5417C3 6.9538 3.2586 6.3957 3.7072 6.0157L6.7072 3.474C7.4532 2.842 8.5468 2.842 9.2928 3.474L10.9186 4.8515M12 21L12 16L16 16L16 21");
}

</style>

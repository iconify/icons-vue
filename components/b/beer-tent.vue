<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eif318bhe"/><path class="v8i71dbdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beer-tent" /></template>
<style>
.eif318bhe {
  d: path("M12.25 17H2.5L10 2.5l5.042 9.748");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8i71dbdt {
  d: path("m7.5 17l2.5-5l2.24 4.481M15 15h4.5v5a1.5 1.5 0 0 1-1.5 1.5h-1.5A1.5 1.5 0 0 1 15 20Zm4.5 1h.5a1.5 1.5 0 0 1 0 3h-.5");
}

</style>

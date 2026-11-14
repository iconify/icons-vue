<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jg_rdmb9q"/><path class="ei8we7kng"/><path class="fup-0ib7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atom-model" /></template>
<style>
.ei8we7kng {
  d: path("M18.75 5.25a9.5 4-45 1 1-13.5 13.5a9.5 4-45 1 1 13.5-13.5Z");
}

.fup-0ib7j {
  d: path("M10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.25 0h.01");
}

.jg_rdmb9q {
  d: path("M5.25 5.25a9.5 4 45 1 1 13.5 13.5a9.5 4 45 1 1-13.5-13.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

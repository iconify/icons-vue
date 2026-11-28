<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jb3959bwr"/><path class="rcgakob0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-search-duotone" /></template>
<style>
.jb3959bwr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.075 18.075 23 12 23C5.925 23 1 18.075 1 12C1 5.925 5.925 1 12 1C18.075 1 23 5.925 23 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rcgakob0m {
  d: path("M13.414 13.414L16.243 16.243M14.357 11.057C14.357 12.88 12.88 14.357 11.057 14.357C9.235 14.357 7.757 12.88 7.757 11.057C7.757 9.235 9.235 7.757 11.057 7.757C12.88 7.757 14.357 9.235 14.357 11.057Z");
}

</style>

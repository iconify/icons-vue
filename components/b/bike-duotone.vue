<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s3u9v8bra"/><path class="cs-7rpbto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bike-duotone" /></template>
<style>
.cs-7rpbto {
  d: path("M12 17L12.8981 13.4076C12.957 13.1719 12.8381 12.928 12.6161 12.8294L9.3302 11.369C8.9701 11.2089 8.9281 10.7146 9.2559 10.496L13.9757 7.3495C14.2437 7.1709 14.6082 7.2884 14.7212 7.59L15.8783 10.6756C15.9515 10.8707 16.1381 11 16.3465 11L18.5 11M17 5C17.5523 5 18 4.5523 18 4C18 3.4477 17.5523 3 17 3C16.4477 3 16 3.4477 16 4C16 4.5523 16.4477 5 17 5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s3u9v8bra {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 17.5C23 19.9853 20.9853 22 18.5 22C16.0147 22 14 19.9853 14 17.5C14 15.0147 16.0147 13 18.5 13C20.9853 13 23 15.0147 23 17.5ZM10 17.5C10 19.9853 7.9853 22 5.5 22C3.0147 22 1 19.9853 1 17.5C1 15.0147 3.0147 13 5.5 13C7.9853 13 10 15.0147 10 17.5Z");
  stroke: none;
}

</style>

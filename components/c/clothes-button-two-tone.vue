<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwinfwbnk"/><path class="afjmqabbu"/><path class="de39xybws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clothes-button-two-tone" /></template>
<style>
.afjmqabbu {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12Z");
}

.cwinfwbnk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.7782 4.2218C21.7677 6.2114 23 8.9627 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C15.0373 1 17.7886 2.2323 19.7782 4.2218Z");
  stroke: none;
}

.de39xybws {
  fill: currentColor;
  d: path("M13.5 8C13.5 8.8284 12.8284 9.5 12 9.5C11.1716 9.5 10.5 8.8284 10.5 8C10.5 7.1716 11.1716 6.5 12 6.5C12.8284 6.5 13.5 7.1716 13.5 8ZM9.5 12C9.5 12.8284 8.8284 13.5 8 13.5C7.1716 13.5 6.5 12.8284 6.5 12C6.5 11.1716 7.1716 10.5 8 10.5C8.8284 10.5 9.5 11.1716 9.5 12ZM17.5 12C17.5 12.8284 16.8284 13.5 16 13.5C15.1716 13.5 14.5 12.8284 14.5 12C14.5 11.1716 15.1716 10.5 16 10.5C16.8284 10.5 17.5 11.1716 17.5 12ZM13.5 16C13.5 16.8284 12.8284 17.5 12 17.5C11.1716 17.5 10.5 16.8284 10.5 16C10.5 15.1716 11.1716 14.5 12 14.5C12.8284 14.5 13.5 15.1716 13.5 16Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

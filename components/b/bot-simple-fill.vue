<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="bsa-eum-k"/><path class="urigu4bfy"/><path class="sp3ujwwyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-simple-fill" /></template>
<style>
.bsa-eum-k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 12C3 9.2386 5.2386 7 8 7L16 7C18.7614 7 21 9.2386 21 12L21 17C21 19.7614 18.7614 22 16 22L8 22C5.2386 22 3 19.7614 3 17L3 12ZM10.5 14.5C10.5 13.6716 9.8284 13 9 13C8.1716 13 7.5 13.6716 7.5 14.5C7.5 15.3284 8.1716 16 9 16C9.8284 16 10.5 15.3284 10.5 14.5ZM16.5 14.5C16.5 13.6716 15.8284 13 15 13C14.1716 13 13.5 13.6716 13.5 14.5C13.5 15.3284 14.1716 16 15 16C15.8284 16 16.5 15.3284 16.5 14.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sp3ujwwyq {
  fill: currentColor;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5Z");
  stroke: none;
}

.urigu4bfy {
  d: path("M12 8L12 3.5");
}

</style>

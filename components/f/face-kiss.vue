<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ae58mzbor"/><path class="migzv_qcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-kiss" /></template>
<style>
.ae58mzbor {
  d: path("M12.349 21.9939C12.2327 21.998 12.1164 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12C22 12.1164 21.998 12.2327 21.9939 12.349M9 10L9 11M15 10L15 11M18.5 22C16.9032 20.7011 15 19.5833 15 17.9167C15 16.8581 15.9402 16 17.1 16C17.625 16 18.0949 16.182 18.5 16.5C18.9051 16.182 19.375 16 19.9 16C21.0598 16 22 16.8581 22 17.9167C22 19.5833 20.0968 20.7011 18.5 22Z");
}

.migzv_qcc {
  fill: currentColor;
  d: path("M12 16.5C12 17.3284 11.3284 18 10.5 18C9.6716 18 9 17.3284 9 16.5C9 15.6716 9.6716 15 10.5 15C11.3284 15 12 15.6716 12 16.5Z");
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

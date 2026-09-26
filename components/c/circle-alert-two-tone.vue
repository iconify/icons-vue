<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iwd1zdb1v"/><path class="afjmqabbu"/><path class="c5yb8bdcb"/><path class="pcr6xabis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-alert-two-tone" /></template>
<style>
.afjmqabbu {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12Z");
}

.c5yb8bdcb {
  d: path("M12 7V13");
}

.iwd1zdb1v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.07513 18.07513 23 12 23C5.92487 23 1 18.07513 1 12C1 5.92487 5.92487 1 12 1C18.07513 1 23 5.92487 23 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pcr6xabis {
  fill: currentColor;
  d: path("M13 17C13 17.55228 12.55228 18 12 18C11.44772 18 11 17.55228 11 17C11 16.44772 11.44772 16 12 16C12.55228 16 13 16.44772 13 17Z");
  stroke: none;
}

</style>

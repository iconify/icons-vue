<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tf3u566vq"/><circle class="qcyv72b4r"/><path class="krnu5gb9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:galaxy-spiral" /></template>
<style>
.krnu5gb9q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5h.01M19 19.5h.01");
}

.qcyv72b4r {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tf3u566vq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.9 10.65c.13.12.64.41.78.75c.14.33.19.8.05 1.27c-.15.48-.46 1.06-.93 1.58c-.48.52-1.16 1.09-1.92 1.53c-.76.43-1.72.85-2.64 1.06c-.92.22-1.99.34-2.88.25c-.9-.09-1.84-.36-2.51-.8c-.66-.45-1.23-1.55-1.48-1.87m5.73-1.07c-.13-.12-.64-.41-.78-.75c-.14-.33-.19-.8-.05-1.27c.15-.48.46-1.06.93-1.58c.48-.52 1.16-1.09 1.92-1.53c.76-.43 1.72-.85 2.64-1.06c.92-.22 1.99-.34 2.88-.25c.9.09 1.84.36 2.51.8c.66.45 1.23 1.55 1.48 1.87");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

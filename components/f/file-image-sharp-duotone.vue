<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vpyvtnijy"/><path clip-rule="evenodd" class="g6hnddcux"/><path class="xzq10fbfs"/><path class="askejtgvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-image-sharp-duotone" /></template>
<style>
.askejtgvc {
  fill: currentColor;
  d: path("M10.5 7C10.5 7.8284 9.8284 8.5 9 8.5C8.1716 8.5 7.5 7.8284 7.5 7C7.5 6.1716 8.1716 5.5 9 5.5C9.8284 5.5 10.5 6.1716 10.5 7Z");
  stroke: none;
}

.g6hnddcux {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 1L14.4142 1L21 7.5858L21 9L13 9ZM15 4.4142L15 7L17.5858 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vpyvtnijy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5196 1.1054 14.7071 1.2929L20.7071 7.2929C20.8946 7.4804 21 7.7348 21 8L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1L14 1Z");
  stroke: none;
}

.xzq10fbfs {
  d: path("M5.7071 16.2929L9.9999 12.0001L18.5528 16.2764");
}

</style>

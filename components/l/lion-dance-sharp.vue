<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uhn17cclo"/><path class="qrk4mcb3i"/><path class="j0f5vuboa"/><path class="ipu148ypm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lion-dance-sharp" /></template>
<style>
.ipu148ypm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14.75h7l1.05.01l-.35.99c-.8 1.75-2.3 2.5-4.2 2.5s-3.4-.75-4.2-2.5l-.35-.99zm2.25 0v1.5m2.5-1.5v1.5");
}

.j0f5vuboa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01m4.99 0h.01");
}

.qrk4mcb3i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 9.75L9.5 8l1.75 1.75m1.5 0L14.5 8l1.75 1.75");
}

.uhn17cclo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6a2.3 2.3 0 0 1 4.11 1.34a2.3 2.3 0 0 1 2.55 3.5a2.3 2.3 0 0 1 0 4.32a2.3 2.3 0 0 1-2.55 3.5A2.3 2.3 0 0 1 12 20a2.3 2.3 0 0 1-4.11-1.34a2.3 2.3 0 0 1-2.55-3.5a2.3 2.3 0 0 1 0-4.32a2.3 2.3 0 0 1 2.55-3.5A2.3 2.3 0 0 1 12 6Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d925dqbjv"/><path class="je8i3lbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-appointment" /></template>
<style>
.d925dqbjv {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4");
}

.je8i3lbag {
  d: path("M12 10.75c-1-1-3.5-1.25-3.5 1.5c0 1.75.75 2.5 1 3.75l.75 2.25H11l1-2.5l1 2.5h.75L14.5 16c.25-1.25 1-2 1-3.75c0-2.75-2.5-2.5-3.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fjy9zxbhs"/><path class="vsuglgbtl"/><path class="l697vccvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-leak" /></template>
<style>
.fjy9zxbhs {
  d: path("M12.82 21.235q-.405.015-.82.015c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.055");
}

.l697vccvo {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m8.5 0c1.5 2 2.75 3.25 2.75 4.75a2.75 2.75 0 0 1-5.5 0c0-1.5 1.25-2.75 2.75-4.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vsuglgbtl {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75c.82 0 1.612-.043 2.358-.124m5.556-2.227A1 1 0 0 0 20 12");
}

</style>

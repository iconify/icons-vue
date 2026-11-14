<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kr6grkbdu"/><path class="u0dh26jds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:defence-shield" /></template>
<style>
.kr6grkbdu {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.5-7.5 10.5c-4-2-7.5-5.5-7.5-10.5V5.5Z");
}

.u0dh26jds {
  d: path("M12 7.25L13 10l3 .25L13.75 12l.75 3l-2.5-1.75L9.5 15l.75-3L8 10.25l3-.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

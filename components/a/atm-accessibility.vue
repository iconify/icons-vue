<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z_bviiqem"/><path class="iwzpfibev"/><path class="otr79_bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-accessibility" /></template>
<style>
.iwzpfibev {
  d: path("M7 5h10v6H7Zm-.5 8.75h7.6m-7.35 3.5h.01m2.49 0h.01M15 19.5V18a3 3 0 0 1 6 0v1.5");
}

.otr79_bye {
  d: path("M14.5 18.5h2v3.25h-2Zm5 0h2v3.25h-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_bviiqem {
  d: path("M11.7 21.5H4v-19h16v10");
}

</style>

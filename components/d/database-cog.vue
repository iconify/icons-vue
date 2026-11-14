<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xwedmfr0m"/><path class="z-zeonh9d"/><path class="fd6bop0xy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-cog" /></template>
<style>
.fd6bop0xy {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m7.942 1.579l.027-1.032h1.062l.027 1.032l.826.477l.907-.492l.532.92l-.881.539v.954l.881.539l-.532.92l-.907-.492l-.826.477l-.027 1.032h-1.062l-.027-1.032l-.826-.477l-.907.492l-.532-.92l.881-.539v-.954l-.881-.539l.532-.92l.907.492Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xwedmfr0m {
  d: path("M13.267 21.215A23 23 0 0 1 12 21.25c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.755");
}

.z-zeonh9d {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q.652 0 1.277-.036");
}

</style>

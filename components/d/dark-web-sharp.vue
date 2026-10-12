<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p97xbpy0c"/><path class="cmnxdfbxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dark-web-sharp" /></template>
<style>
.cmnxdfbxg {
  d: path("M12 10c-2 1.75-3.25 3.5-3.25 5.5S10 19 12 19m0-9c2 1.75 3.25 3.5 3.25 5.5S14 19 12 19m0-9v9m0-14.5l1.05-1.75h2.2");
}

.p97xbpy0c {
  d: path("m12 4.5l-.618 2.474L9.25 8.75c-2.5 2-4.25 4-4.25 6.5a7 6 0 0 0 14 0c0-2.5-1.75-4.5-4.25-6.5l-2.132-1.776z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

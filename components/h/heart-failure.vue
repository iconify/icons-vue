<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hl0n0l42o"/><path class="kewsbackd"/><path class="i_wa5ybab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-failure" /></template>
<style>
.hl0n0l42o {
  d: path("M11.429 16.009C10.588 16.635 10 17 10 17s-7.25-4.5-7.25-9c0-2.25 1.75-4 3.75-4C8 4 9.25 5 10 6c.75-1 2-2 3.5-2c2 0 3.75 1.75 3.75 4c0 1.445-.747 2.89-1.762 4.185");
}

.i_wa5ybab {
  d: path("M19 19.5h2.75v-2.75");
}

.kewsbackd {
  d: path("m10 9l-1.25 2L11 12l-1.25 2m4.5 1L17 18l2-1.75l2.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

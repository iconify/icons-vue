<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sukgh2b7c"/><path class="n286cdc8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:landing-page-stats" /></template>
<style>
.n286cdc8t {
  d: path("M15.25 16.25v4.5h4.5");
}

.sukgh2b7c {
  d: path("M12.4 21.5H3.5v-19h17v9.1M3.5 7h17m-14-2.25h.01m2.74 0h.01M7 11h10M7 14.5h5m9.25.25L15.5 20.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

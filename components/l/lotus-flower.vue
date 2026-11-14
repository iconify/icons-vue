<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bakqavquc"/><path class="kqgty2gud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lotus-flower" /></template>
<style>
.bakqavquc {
  d: path("M12 3c3 3 3 8 0 12c-3-4-3-9 0-12Z");
}

.kqgty2gud {
  d: path("M12 15c-4 0-8-2.5-9-6.5c4 0 7.5 2.5 9 6.5m0 0c4 0 8-2.5 9-6.5c-4 0-7.5 2.5-9 6.5m-6 5h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

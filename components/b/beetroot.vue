<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="otqd9vilh"/><path class="e0o5k_bup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beetroot" /></template>
<style>
.e0o5k_bup {
  d: path("M12 7.5c-4 0-6-2.25-5.5-4.25C10 3.25 12 5 12 7.5Zm0 0c4 0 6-2.25 5.5-4.25C14 3.25 12 5 12 7.5Z");
}

.otqd9vilh {
  d: path("M12 20.75C11 19 5.5 18.5 5.5 14a6.5 6.5 0 0 1 13 0c0 4.5-5.5 5-6.5 6.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

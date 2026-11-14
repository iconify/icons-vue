<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="evgmc0bvt"/><path class="n2k9n8zij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balloon-letters" /></template>
<style>
.evgmc0bvt {
  d: path("M5 9.5a7 7.5 0 1 0 14 0a7 7.5 0 1 0-14 0Z");
}

.n2k9n8zij {
  d: path("M12 17q-1.25 2.25.5 4.5M9.75 13L12 6.5l2.25 6.5m-3.75-2.25h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

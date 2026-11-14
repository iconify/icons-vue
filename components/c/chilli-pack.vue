<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xhzm3vo3a"/><path class="pvz-3bcvu"/><path class="f-61yubuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chilli-pack" /></template>
<style>
.f-61yubuh {
  d: path("M16 7.5q.5-3.25 3.5-5");
}

.pvz-3bcvu {
  d: path("M12.25 9.5Q15.5 6 19 9.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhzm3vo3a {
  d: path("M16 7.5c4 2 3.5 7-1 10.5c-3.5 2.75-8 3.5-11.5 3c4-1.5 7-4.5 8-9c.75-3 2.5-4.5 4.5-4.5Z");
}

</style>

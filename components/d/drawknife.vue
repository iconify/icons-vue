<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a-p6as2ow"/><path class="b0wwv9blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drawknife" /></template>
<style>
.a-p6as2ow {
  d: path("M8.25 6.5h7.5L14.5 11h-5Z");
}

.b0wwv9blu {
  d: path("m5.124 4.227l3.447.607L6.14 18.622l-3.447-.608Zm10.305.607l3.447-.607l2.431 13.787l-3.447.608Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

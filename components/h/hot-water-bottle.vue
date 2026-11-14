<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hgew2ubds"/><path class="p4h-ntcev"/><path class="g773wi9gq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-water-bottle" /></template>
<style>
.g773wi9gq {
  d: path("m6.573 3.898l4.698-1.71l.77 2.114l-4.699 1.71Zm3.292 10.507l5.638-2.052m-4.526 5.106l5.638-2.052");
}

.hgew2ubds {
  d: path("m9.051 7.784l-3.202 4.359l3.42 9.397l11.276-4.105l-3.42-9.397l-5.255-1.28Z");
}

.p4h-ntcev {
  d: path("m8.282 5.67l2.819-1.026l.769 2.114l-2.819 1.026Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

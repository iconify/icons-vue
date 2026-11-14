<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ocyf5ip6z"/><path class="icah34qim"/><path class="yl5sb2bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headscarf" /></template>
<style>
.icah34qim {
  fill: currentColor;
  d: path("M4.5 10.5C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.25c-4-1.5-10-.75-14.5 1.25Zm-1.75 3a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ocyf5ip6z {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25c0 1.1-.9 2-2 2h-2v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yl5sb2bgf {
  d: path("m3.75 15l-1 3.5m2-3.5l.5 3.5m11.5-7.5h.01");
}

</style>

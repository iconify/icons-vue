<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c934u-b-i"/><path class="fvh-tji7f"/><path class="rs3zhe-tj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-deposit-cheque" /></template>
<style>
.c934u-b-i {
  d: path("M10.9 21.5H4v-19h16v9.2");
}

.fvh-tji7f {
  d: path("M7 5h10v6H7Zm-.5 8.75h4.4m-4.15 3.5h.01m2.49 0h.01m4.49-2.75h8v7h-8ZM15.5 17h4.25");
}

.rs3zhe-tj {
  d: path("m15.5 19.75l1-1l1 1l1-1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

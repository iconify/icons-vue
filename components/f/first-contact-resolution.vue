<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l0km1xbre"/><path class="aa_bxhb2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-contact-resolution" /></template>
<style>
.aa_bxhb2u {
  d: path("m8 11l3 3l5-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0km1xbre {
  d: path("M12 3.5c5.25 0 9 3.25 9 7.5s-3.75 7.5-9 7.5c-1.25 0-2.5-.25-3.5-.5L4 20.5l1-4.25C3.75 14.75 3 13 3 11c0-4.25 3.75-7.5 9-7.5");
}

</style>

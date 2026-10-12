<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mgiids75u"/><path class="ezf0qz7-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gdpr-shield-sharp" /></template>
<style>
.ezf0qz7-t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.6 11.4h.01m-1.06 2.55h.01M12 15h.01m-2.56-1.05h.01M8.4 11.4h.01m1.04-2.55h.01M12 7.8h.01m2.54 1.05h.01");
}

.mgiids75u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l6.6 2.45l.652.244l-.002.696v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14l-.002-.696L5.4 5.2Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

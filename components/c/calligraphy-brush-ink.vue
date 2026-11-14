<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6qd2cbfs"/><path class="mu2l_nb5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calligraphy-brush-ink" /></template>
<style>
.e6qd2cbfs {
  d: path("M18.425 4.575za2 2 0 0 1 0 2.829l-4.243 4.242a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828l4.242-4.243a2 2 0 0 1 2.829 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mu2l_nb5e {
  d: path("m11.262 11.554l.184.184a1.5 1.5 0 0 1-.256 2.327l-2.311 1.471a1.024 1.024 0 0 1-1.415-1.415l1.471-2.311a1.5 1.5 0 0 1 2.327-.256M16 13.5s-2.5 3-2.5 4.5a2.5 2.5 0 0 0 5 0c0-1.5-2.5-4.5-2.5-4.5");
}

</style>

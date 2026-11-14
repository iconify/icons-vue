<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwlg6i9ba"/><path class="ul9kl856c"/><path class="s36oc647h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bee" /></template>
<style>
.s36oc647h {
  d: path("M2.5 9.5a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0Zm12 0a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0ZM11 4L9.5 2.5M13 4l1.5-1.5M7.5 13h9M8 16.5h8");
}

.ul9kl856c {
  d: path("M7.5 14.25a4.5 6.25 0 1 0 9 0a4.5 6.25 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwlg6i9ba {
  d: path("M10 5.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>

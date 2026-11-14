<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bdy5jq4he"/><path class="plw6p44fa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kids-scooter-three-wheel" /></template>
<style>
.bdy5jq4he {
  d: path("m4.5 19.5l2-4h8.75m-2.5 4L16 14l3.5 5.5M16 14L14.5 3.5m-2.5 0h5");
}

.plw6p44fa {
  d: path("M2.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8.25 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.75 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

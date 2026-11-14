<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r02fzqbhp"/><path class="c0sua3x1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-park" /></template>
<style>
.c0sua3x1g {
  d: path("M10.75 21.5v-4h2.5v4m-8-6.5h.01M12 10h.01m6.74 3h.01");
}

.r02fzqbhp {
  d: path("M2.5 21.5V11H8V5h2V3h4v2h2v3h5.5v13.5ZM8 11v10.5M16 8v13.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

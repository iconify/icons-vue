<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j2puqebga"/><path class="nym36acms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hanbok" /></template>
<style>
.j2puqebga {
  d: path("M9.5 3h5l6 5l-2 2.5L15 8v1H9V8l-3.5 2.5l-2-2.5Z");
}

.nym36acms {
  d: path("M9 9L4.5 21h15L15 9M9.5 3L12 7l2.5-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

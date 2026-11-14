<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zgr--obdy"/><path class="wo1bz4wpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:french-doors" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wo1bz4wpy {
  d: path("M6.25 5.5H9.5v6H6.25Zm8.25 0h3.25v6H14.5Zm-4 9.5h.01m2.99 0h.01");
}

.zgr--obdy {
  d: path("M4 3h16v18H4Zm8 0v18");
}

</style>

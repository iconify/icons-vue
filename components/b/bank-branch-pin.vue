<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kz-wmbc0j"/><path class="zkmu6fjwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-branch-pin" /></template>
<style>
.kz-wmbc0j {
  d: path("M12 21.5c-4-4-7.5-7.75-7.5-11.75a7.5 7.5 0 0 1 15 0c0 4-3.5 7.75-7.5 11.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zkmu6fjwo {
  d: path("M8 9.5L12 6l4 3.5Zm1.25 0v4m2.75-4v4m2.75-4v4M8 13.5h8");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok4pqkb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crevice-tool" /></template>
<style>
.ok4pqkb3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.192 6.056l.995.11a.846.846 0 0 1 .549 1.393l-6.389 7.454a1.5 1.5 0 0 1-2.199.084l-1.176-1.175a1.5 1.5 0 0 1 .154-2.255l6.993-5.315a1.5 1.5 0 0 1 1.073-.296m-8.286 7.8l1.238 1.238a2.625 2.625 0 0 1 0 3.712l-.53.53a2.625 2.625 0 0 1-3.713 0l-1.237-1.237a2.625 2.625 0 0 1 0-3.713l.53-.53a2.625 2.625 0 0 1 3.712 0");
}

</style>

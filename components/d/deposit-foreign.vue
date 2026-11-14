<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nw0zjbr6k"/><path class="qclu_qbqg"/><path class="ur0npetif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-foreign" /></template>
<style>
.nw0zjbr6k {
  d: path("M11.945 18c-.72 0-1.213-.006-1.945-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6s8 2.5 8 6q0 .116-.004.23");
}

.qclu_qbqg {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m1.25 9.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm0 0h6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ur0npetif {
  d: path("M16.75 18a1.25 3.25 0 1 0 2.5 0a1.25 3.25 0 1 0-2.5 0Z");
}

</style>

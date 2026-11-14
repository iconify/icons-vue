<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s-iw93b_k"/><path class="a1exfaclq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:angle-grinder" /></template>
<style>
.a1exfaclq {
  d: path("M15 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.s-iw93b_k {
  d: path("M2.5 10.5h9v5h-9Zm9 2.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM7 10.5V5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hwqaa7bbv"/><path class="bz1u23b0o"/><path class="l7fe2lblv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brand-kit" /></template>
<style>
.bz1u23b0o {
  d: path("M4 11V4.5a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2V13");
}

.hwqaa7bbv {
  d: path("M2.5 13a2 2 0 0 1 2-2H9l2 2h8.5a2 2 0 0 1 2 2v4.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

.l7fe2lblv {
  d: path("M5.75 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.75-1.5h3v3h-3Zm4.75 3l1.5-3l1.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="myx7qnt-b"/><path class="nzw_hdb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:incidental-charges" /></template>
<style>
.myx7qnt-b {
  d: path("M17.25 7h2.5a1 1 0 0 1 1 1v13.5l-2-1.5l-2 1.5l-2-1.5l-2 1.5l-2-1.5v-6.5");
}

.nzw_hdb-o {
  d: path("M3.25 4h14v9.5h-14Zm10.5 12.75h4M3.25 7.5h14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

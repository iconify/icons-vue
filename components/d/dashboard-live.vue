<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fh_gg4rpc"/><path class="figndx1lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-live" /></template>
<style>
.fh_gg4rpc {
  d: path("M13 21.5H2.5v-19h19v11.2M2.5 11h19M11 11v10.5");
}

.figndx1lm {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5m0 13h.01m2.288-1.928a3 3 0 0 1 0 3.856m-4.596 0a3 3 0 0 1 0-3.856");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

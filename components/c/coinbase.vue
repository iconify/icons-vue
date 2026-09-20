<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jng6ewb0q"/><path clip-rule="evenodd" class="wmt2psbil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:coinbase" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jng6ewb0q {
  fill: var(--svg-color--0e5bff, #0e5bff);
  d: path("M3 12a9 9 0 1 1 18 0a9 9 0 0 1-18 0");
}

.wmt2psbil {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 18.375a6.375 6.375 0 1 0 0-12.75a6.375 6.375 0 0 0 0 12.75m-.75-8.25c-.621 0-1.125.504-1.125 1.125v1.5c0 .621.504 1.125 1.125 1.125h1.5c.621 0 1.125-.504 1.125-1.125v-1.5c0-.621-.504-1.125-1.125-1.125z");
}

</style>

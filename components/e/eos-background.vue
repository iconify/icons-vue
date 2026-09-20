<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="p9bqzeyyi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eos-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.p9bqzeyyi {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.876 4.04a.203.203 0 0 1 .285.043l3.462 4.727a.2.2 0 0 1 .034.074l1.677 7.27a.21.21 0 0 1-.082.213l-5.103 3.565a.204.204 0 0 1-.269.031l-5.133-3.596a.2.2 0 0 1-.082-.213l1.677-7.27a.2.2 0 0 1 .034-.074l3.435-4.692a.2.2 0 0 1 .065-.079m.123.512L8.766 8.97l2.236 7.026h1.99l2.241-7.029zM15.427 9.7l-2.007 6.296h3.46zm1.061 6.704H13.29l-.916 2.873zm-4.492 2.717l.866-2.717h-1.73zm-1.422-3.125L8.572 9.705l-1.45 6.291zm-3.063.408h3.193l.916 2.879z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

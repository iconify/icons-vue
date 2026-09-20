<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="flrqk9b-q"/><path class="hhzcy0bsm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kucoin-background" /></template>
<style>
.flrqk9b-q {
  fill: var(--svg-color--23af91, #23af91);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hhzcy0bsm {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.337 12l4.653 4.74l2.944-2.988a1.33 1.33 0 0 1 1.881 0a1.38 1.38 0 0 1 0 1.913l-3.88 3.949a1.34 1.34 0 0 1-1.882 0l-5.68-5.693v3.38a1.323 1.323 0 0 1-1.287 1.352c-.736-.01-1.296-.625-1.286-1.352V6.7c0-.747.548-1.352 1.286-1.352c.73 0 1.286.605 1.286 1.352v3.38l5.682-5.693a1.34 1.34 0 0 1 1.881 0l3.87 3.95a1.38 1.38 0 0 1 0 1.912a1.33 1.33 0 0 1-1.871 0l-2.944-2.99zm4.662-1.352c.73 0 1.323.605 1.323 1.352s-.594 1.352-1.323 1.352s-1.332-.605-1.332-1.352s.594-1.352 1.332-1.352");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

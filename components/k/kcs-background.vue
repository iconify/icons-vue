<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="flrqk9b-q"/><path class="y7s13rb6a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kcs-background" /></template>
<style>
.flrqk9b-q {
  fill: var(--svg-color--23af91, #23af91);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y7s13rb6a {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.369 12l4.598 4.74l2.907-2.988c.5-.52 1.36-.52 1.86 0a1.393 1.393 0 0 1 0 1.913L14.9 19.614a1.31 1.31 0 0 1-1.859 0L7.428 13.92v3.38c.01.724-.547 1.338-1.27 1.352c-.727-.01-1.28-.625-1.271-1.352V6.7c0-.747.541-1.352 1.27-1.352c.72 0 1.271.605 1.271 1.352v3.38l5.613-5.693a1.31 1.31 0 0 1 1.86 0l3.823 3.95a1.39 1.39 0 0 1 0 1.912c-.5.514-1.35.514-1.85 0l-2.907-2.99zm4.606-1.352c.72 0 1.308.605 1.308 1.352s-.588 1.352-1.308 1.352S12.66 12.747 12.66 12s.587-1.352 1.316-1.352");
}

</style>

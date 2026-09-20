<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nf4g84w5z"/><path class="cu_nj4jfs"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:edge-background" /></template>
<style>
.cu_nj4jfs {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.999 12q0-.191-.01-.381q-.007-.131-.019-.261q-.001-.051-.007-.102a8 8 0 0 0-.04-.333v-.018a8 8 0 1 0-1.67 6.084l-2.455-1.748C14.791 16.419 13.441 17 12.004 17A4.986 4.986 0 0 1 7 12a4.98 4.98 0 0 1 5-4.998a4.99 4.99 0 0 1 4.77 3.5h-4.766l-1.277 3h9.14c.068-.379.11-.814.123-1.198c.006-.08.009-.178.009-.303");
}

.ft5dv1b6b {
  fill: none;
}

.nf4g84w5z {
  fill: var(--svg-color--0ecc5f, #0ecc5f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGCxxDuKBj)" class="sqp76cc2c"/><path class="innb2ldyv"/><defs><linearGradient id="SVGCxxDuKBj" x1="19.92" x2="8.13" y1="4.588" y2="15.092" gradientUnits="userSpaceOnUse"><stop class="j7zeu_quw"/><stop offset="1" class="osubsuaxa"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:3ull" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.innb2ldyv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.276 8.944c-.355-.73-1.568-.73-2.981-1.1c-1.128-.292-.942-1.589-.704-2.198c-1.133.291-1.414.974-1.414 1.588c0 2.198 2.557 2.446 2.912 2.806c.28.297.116.615 0 .742c-.28.873.736 1.503 1.324 1.747v1.588c0 .37.598 1.059 1.588 1.059s1.588-.689 1.588-1.06V12.53c0-.371 1.678-1.017 1.324-1.747c-.281-.593-.117-.742 0-.742c1.413-.36 2.911-2.011 2.911-2.806s-.264-1.323-1.323-1.588c.264.265.407 1.615-.44 2.197c-1.059.736-2.98.37-3.335 1.101c-.28.583-.116 1.71 0 2.198l1.218-.366c0 .736-.498 1.101-.847 1.101c-.355 0-.832.55-.832.916c0 .37 0 1.06-.264 1.06c-.265 0-.265-.816-.265-1.06c0-.37-.265-.916-.826-.916c-.566 0-.73-.735-.73-1.1l1.095.37c.233-.492.281-1.615 0-2.203");
}

.j7zeu_quw {
  stop-color: var(--svg-color--15493c, #15493c);
}

.osubsuaxa {
  stop-color: var(--svg-color--069a35, #069a35);
}

.sqp76cc2c {
  d: path("M21 4.588H3l9 14.824z");
}

</style>

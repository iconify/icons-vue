<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="dzl0tcbrf"/><path clip-rule="evenodd" class="j-0ln4byn"/><path class="zahoplurb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ertha-background" /></template>
<style>
.dzl0tcbrf {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.4 14.936V10.2H4L4.468 9H6.68l-.072 1.2H5.6v1.2h.888l-.068 1.2H5.6v1.2h1.08l-.052.96c-.796.048-1.44.108-2.228.176M20 15l-.768-6h-2.008l-.468 1.2h.528l-.672 4.532l1.152.072l.096-.604h.964l.108.692c.396.032.676.068 1.068.108m-1.656-4.128l.32 2.128h-.64z");
}

.ft5dv1b6b {
  fill: none;
}

.j-0ln4byn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m10.052 14.6l-.42-1.457A1.32 1.32 0 0 0 10 12.2v-1.96q.001-.658-.292-.944c-.192-.196-.588-.292-1.032-.292h-1.52l-.468 1.2H7.2v4.528l1.2-.056V13.4h.2l.34 1.2zm-1.296-4.4H8.4v2h.36c.024 0 .04-.017.04-.04v-1.92q-.002-.039-.04-.04z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zahoplurb {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.4 14.708V9h-1.2v2.8h-.8V9h-1.24l-.36 1.2V9h-2.59L10 10.2h.8v4.4H12v-4.4h1.2v4.4h1.2v-2h.8v2.056q.6.022 1.2.052");
}

</style>

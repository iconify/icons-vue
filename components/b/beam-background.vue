<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q66t-_84h"/><path class="l9nfmgj9r"/><path class="zbyyqjlsc"/><path class="br4uorb0a"/><path class="qofl8ug7z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:beam-background" /></template>
<style>
.br4uorb0a {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 9.905l7.992 3.696v.388L4 12.24zm16-1.077l-8.008 4.776v.132L20 10.372z");
}

.ft5dv1b6b {
  fill: none;
}

.l9nfmgj9r {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 15.6h3.32L12 10V6.4l6.8 11.2H12zm0 0H8.664L12 10V6.4L5.2 17.6H12z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q66t-_84h {
  fill: var(--svg-color--0b76ff, #0b76ff);
  d: path("M24 0H0v24h24z");
}

.qofl8ug7z {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 13.457l-8.008.535v-.128L20 11.912zm0-3.085l-8.008 3.36v.132L20 11.912z");
}

.zbyyqjlsc {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 11.6v3.2h-2zm0 0v3.2h2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t4uocqbni"/><path class="gekzoyb5s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:iron-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gekzoyb5s {
  fill: var(--svg-color--000, #000);
  d: path("m19.954 11.831l-2.61-4.294a.37.37 0 0 0-.312-.169H11.81a.37.37 0 0 0-.307.169l-2.147 3.545a.168.168 0 0 1-.27.018a.16.16 0 0 1-.033-.094V9.722c0-1.297-1.205-2.354-2.569-2.354H4.362c-.194 0-.362.16-.362.341v2.013c0 .93.69 1.79 1.587 2.139c.06.025.097.08.097.139a.16.16 0 0 1-.097.143C4.687 12.488 4 13.347 4 14.278v2.008c0 .19.168.345.362.345H6.48c1.368 0 2.568-1.057 2.568-2.358v-1.28a.156.156 0 0 1 .16-.151a.17.17 0 0 1 .144.076l2.147 3.54a.38.38 0 0 0 .316.173h5.217a.37.37 0 0 0 .311-.168l2.61-4.295a.33.33 0 0 0 0-.337m-5.428 1.853a1.684 1.684 0 1 1 0-3.369a1.684 1.684 0 0 1 0 3.369");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t4uocqbni {
  fill: var(--svg-color--ee99d0, #ee99d0);
  d: path("M24 0H0v24h24z");
}

</style>

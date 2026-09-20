<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ka4nepbcp"/><path class="pljso8t8k"/><path class="w_1wqnbbg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hubble-exchange-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ka4nepbcp {
  fill: var(--svg-color--5c25f8, #5c25f8);
  d: path("M24 0H0v24h24z");
}

.pljso8t8k {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.403 4.122v2.015a6.026 6.026 0 0 1 2.85 10.138a6.03 6.03 0 0 1-3.802 1.736v-1.37a4.661 4.661 0 0 0 .16-9.263v2.167a2.528 2.528 0 0 0-2.624 3.981l.447-.446a1.906 1.906 0 0 1 2.647-2.65l.446-.446a2.5 2.5 0 0 0-.58-.33V8.617a3.512 3.512 0 0 1-.941 6.895V20q.226 0 .447-.012a8 8 0 0 0 7.533-7.51a8 8 0 0 0-6.583-8.356M14.53 12c0-.58-.2-1.144-.566-1.594l-.444.444a1.905 1.905 0 0 1-2.668 2.669l-.444.443q.296.242.648.384v1.037a3.511 3.511 0 0 1 .945-6.895V4a8 8 0 0 0-7.97 7.298a8 8 0 0 0 6.57 8.58v-2.017A6.027 6.027 0 0 1 7.759 7.728a6.03 6.03 0 0 1 3.796-1.739v1.37a4.661 4.661 0 0 0-.16 9.263v-2.167A2.53 2.53 0 0 0 14.53 12");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w_1wqnbbg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.17 12a1.167 1.167 0 1 1-.09-.443c.06.141.09.293.09.446z");
}

</style>

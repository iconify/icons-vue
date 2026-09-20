<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="prnodabrv"/><path class="lvinwjbxm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lvinwjbxm {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.676 4.092C10.857 4.755 9.6 6.17 9.6 7.832a2.325 2.325 0 0 0 2.335 2.316a2.325 2.325 0 0 0 2.334-2.316c0-1.663-1.255-3.077-2.075-3.74a.41.41 0 0 0-.52 0m.26 9.76A2.325 2.325 0 0 0 9.6 16.167c0 1.664 1.256 3.078 2.075 3.74a.41.41 0 0 0 .52 0c.819-.662 2.074-2.076 2.074-3.74a2.325 2.325 0 0 0-2.334-2.315m4.2.463A2.325 2.325 0 0 1 13.802 12a2.325 2.325 0 0 1 2.334-2.315c1.678 0 3.103 1.244 3.771 2.057a.4.4 0 0 1 0 .515c-.668.813-2.094 2.058-3.77 2.058M4.093 11.743c.668-.814 2.094-2.058 3.77-2.058A2.325 2.325 0 0 1 10.199 12a2.325 2.325 0 0 1-2.334 2.315c-1.678 0-3.103-1.245-3.771-2.058a.4.4 0 0 1 0-.514");
}

.prnodabrv {
  fill: var(--svg-color--616ae9, #616ae9);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

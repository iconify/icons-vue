<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="a0a9m5bqc"/><path class="lmlqqvbgg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:coin98-background" /></template>
<style>
.a0a9m5bqc {
  fill: var(--svg-color--d9b432, #d9b432);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.lmlqqvbgg {
  fill: var(--svg-color--000, #000);
  d: path("M17.079 4H6.921A2.913 2.913 0 0 0 4 6.922v10.156A2.913 2.913 0 0 0 6.922 20h10.156A2.927 2.927 0 0 0 20 17.078V6.922A2.913 2.913 0 0 0 17.078 4m-2.466 3.994c1.187 0 2.146.959 2.146 2.146c0 .365-.091.707-.251 1.027a3.4 3.4 0 0 0-.89-.502a1.06 1.06 0 0 0 .137-.525a1.12 1.12 0 0 0-1.119-1.119a1.12 1.12 0 0 0-1.118 1.119c0 .182.045.365.137.525c-.32.114-.64.274-.89.502a2 2 0 0 1-.251-1.027c-.046-1.187.913-2.146 2.1-2.146m-5.226 8.012A2.143 2.143 0 0 1 7.24 13.86h1.027a1.12 1.12 0 0 0 1.119 1.119a1.12 1.12 0 0 0 1.118-1.119h1.027a2.143 2.143 0 0 1-2.145 2.146m0-3.013a2.494 2.494 0 0 1-2.488-2.488c0-1.37 1.118-2.51 2.488-2.51s2.51 1.118 2.51 2.51c-.023 1.37-1.14 2.488-2.51 2.488m5.226 3.013c-1.37 0-2.51-1.119-2.51-2.488a2.499 2.499 0 1 1 4.999 0a2.494 2.494 0 0 1-2.489 2.488m1.484-2.511c0 .822-.662 1.46-1.484 1.46a1.476 1.476 0 0 1-1.483-1.46a1.48 1.48 0 0 1 1.483-1.484c.822.023 1.484.685 1.484 1.484m-5.25-2.99a1.48 1.48 0 0 1-1.483 1.484a1.48 1.48 0 0 1-1.484-1.484a1.48 1.48 0 0 1 1.484-1.484c.844 0 1.483.662 1.483 1.484");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

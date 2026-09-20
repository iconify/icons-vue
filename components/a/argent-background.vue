<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f6352gb_j"/><path class="bh5ao0bwe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:argent-background" /></template>
<style>
.bh5ao0bwe {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.059 4.8H9.94a.254.254 0 0 0-.25.252c-.084 3.93-2.107 7.66-5.589 10.302a.26.26 0 0 0-.055.354l2.41 3.386a.25.25 0 0 0 .353.056c2.178-1.64 3.929-3.62 5.19-5.815c1.261 2.195 3.012 4.174 5.19 5.815a.25.25 0 0 0 .354-.056l2.409-3.386a.26.26 0 0 0-.055-.354c-3.482-2.642-5.505-6.372-5.588-10.302a.254.254 0 0 0-.251-.252");
}

.f6352gb_j {
  fill: var(--svg-color--ff875b, #ff875b);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

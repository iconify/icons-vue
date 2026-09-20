<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="hd5uubbkd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bnb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hd5uubbkd {
  fill: var(--svg-color--f0b90b, #f0b90b);
  d: path("M7.454 6.449L12 4l4.547 2.449l-1.667.907L12 5.809L9.125 7.356zm9.093 3.093l-1.667-.906L12 10.182L9.125 8.636l-1.671.906v1.81l2.87 1.546v3.089l1.676.906l1.672-.906v-3.09l2.875-1.546zm0 4.903V12.63l-1.667.907v1.809zm1.19.64l-2.876 1.542v1.813l4.547-2.453v-4.898l-1.672.902zm-1.672-7.09l1.667.907v1.81l1.676-.903V7.996l-1.672-.907L16.065 8zm-5.74 9.29v1.808L12 20l1.672-.907V17.29l-1.672.9l-1.671-.907zM7.453 14.44l1.667.907v-1.81l-1.667-.906v1.813zm2.87-6.444L12 8.902l1.672-.906L12 7.089L10.33 8zm-4.06.906l1.671-.906l-1.666-.907L4.593 8v1.813l1.671.903V8.902m0 3.09l-1.671-.903v4.898l4.546 2.453v-1.818L6.27 15.08v-3.093z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

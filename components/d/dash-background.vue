<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vpxewrb8v"/><path class="h-xd7bcra"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dash-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h-xd7bcra {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.693 11.128q-.124.959-.387 1.889c-.516 1.9-2.395 2.591-4.207 2.596H6.787c-.01 0-.015.016-.015.026l-.568 3.046c0 .015.01.026.02.026h6.015q.925.005 1.842-.114a6.3 6.3 0 0 0 2.339-.805c1.745-1.007 2.736-2.865 3.2-4.806c.227-.966.362-1.91.377-2.824c.036-1.332-.268-2.715-1.28-3.629a5 5 0 0 0-2.669-1.13a10.5 10.5 0 0 0-1.512-.114H8.532c-.01 0-.015 0-.015.016l-.49 3.082h5.497c.831 0 2.344.02 2.834.763c.372.568.408 1.332.33 1.978zm-11.062-.62c-.722.155-1.135.687-1.3 1.43A41 41 0 0 0 4 13.548h5.936q.348.002.579-.036a1.6 1.6 0 0 0 1.321-1.135c.051-.15.093-.29.124-.429q.158-.746.294-1.497H6.085c-.144 0-.294.021-.454.052z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vpxewrb8v {
  fill: var(--svg-color--008de4, #008de4);
  d: path("M24 0H0v24h24z");
}

</style>

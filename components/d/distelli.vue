<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":236};
const content = `<path class="vext0b15n"/><path class="bv509tv5g"/><path class="xpf-nbkqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:distelli" /></template>
<style>
.bv509tv5g {
  d: path("M221.84 92.624h-56.595a5.738 5.738 0 0 0-4.968 2.868l-28.298 49.013a5.738 5.738 0 0 0 0 5.737l28.298 49.012a5.737 5.737 0 0 0 4.968 2.868h56.594a5.737 5.737 0 0 0 4.969-2.868l28.297-49.012a5.738 5.738 0 0 0 0-5.737l-28.297-49.013a5.738 5.738 0 0 0-4.969-2.868");
  fill: var(--svg-color--4eba6f, #4EBA6F);
}

.vext0b15n {
  d: path("M118.355.36h-73.83a7.482 7.482 0 0 0-6.48 3.741L1.128 68.04a7.485 7.485 0 0 0 0 7.484l36.915 63.938a7.483 7.483 0 0 0 6.481 3.742h73.83a7.485 7.485 0 0 0 6.481-3.742l36.915-63.938a7.482 7.482 0 0 0 0-7.484L124.836 4.101a7.484 7.484 0 0 0-6.48-3.742");
  fill: var(--svg-color--3b97d3, #3B97D3);
}

.xpf-nbkqw {
  d: path("M120.29 151.74H77.111a4.377 4.377 0 0 0-3.79 2.189l-21.589 37.392a4.376 4.376 0 0 0 0 4.377l21.588 37.393a4.377 4.377 0 0 0 3.79 2.188h43.178a4.377 4.377 0 0 0 3.79-2.188l21.589-37.393a4.376 4.376 0 0 0 0-4.377l-21.589-37.392a4.377 4.377 0 0 0-3.79-2.188");
  fill: var(--svg-color--f0c419, #F0C419);
}

</style>

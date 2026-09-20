<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="scwa-tfaw"/><path clip-rule="evenodd" class="njmqkoq3q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:defit-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.njmqkoq3q {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.965 7.675h-1.393l.368-1.298h-1.406l-.42 1.298H5.09l1.107 1.57L4 16.325h4.407l-.42 1.297h1.467l.367-1.297h1.436l-.415 1.297h1.462l.372-1.297h3.533a1.96 1.96 0 0 0 1.865-1.375l1.88-6a.982.982 0 0 0-.929-1.275h-3.607l.368-1.298H14.38l-.42 1.298zm-.013 6.487l1.384-4.325H9.93l-.416 1.298h1.882l-.459 1.297H9.095l-.554 1.73z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.scwa-tfaw {
  fill: var(--svg-color--037cff, #037cff);
  d: path("M24 0H0v24h24z");
}

</style>

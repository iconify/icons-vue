<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tyx6r4e5k"/><path class="gx-y4acwb"/><path class="t5ymtu7-n"/><path clip-rule="evenodd" class="q-h6h9f0t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:luca-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gx-y4acwb {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.53 5.882a.94.94 0 1 0-.815-1.411h-4.363v.94h4.363c.16.283.466.471.814.471m0 3.765a.94.94 0 1 0-.815-1.411h-4.363v.94h4.363c.16.283.466.471.814.471M17.411 20a.941.941 0 1 0 0-1.882a.941.941 0 0 0 0 1.882");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-h6h9f0t {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.091 4.47c-1.12 0-2.033.74-2.033 1.836c-.979 0-1.882.927-1.882 1.882v7.671c0 .988.819 1.788 1.826 1.788c0 1.069.885 1.883 1.976 1.883h7.893c.145.212.263 0 .54 0c.448 0 .942-.01.942-.447c0-.438-.494-.494-.941-.494c-.302 0-.433-.236-.575 0H8.978c-.616 0-1.115-.34-1.115-.942h7.196v-2.823H9.882V4.47zm-.15.941v9.413h-.942V6.306c0-.546.382-.895.942-.895M7.058 7.294c-.503 0-.941.405-.941.894v7.822c.033.442.376.696.833.696h7.167v-.941H7.059z");
}

.t5ymtu7-n {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.882 7.764a.94.94 0 1 0-.814-1.412h-6.716v.941h6.716c.16.283.466.47.814.47");
}

.tyx6r4e5k {
  fill: var(--svg-color--faca8c, #faca8c);
  d: path("M24 0H0v24h24z");
}

</style>

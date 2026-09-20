<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c-jy-actb"/><path clip-rule="evenodd" class="xfctzvbix"/><path class="iqtdevbgp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dafi-background" /></template>
<style>
.c-jy-actb {
  fill: var(--svg-color--33363c, #33363c);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.iqtdevbgp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 7.394c1.251 0 2.415.363 3.395.99v4.829h-.034a3.395 3.395 0 0 0-6.722 0H5.715A6.304 6.304 0 0 1 12 7.393");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xfctzvbix {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.364 4a.97.97 0 0 0-.97.97v3.414a6.304 6.304 0 1 0 2.91 5.315v-8.73a.97.97 0 0 0-.97-.969zm-.97 9.699a3.394 3.394 0 1 0-6.789 0a3.394 3.394 0 0 0 6.79 0");
}

</style>

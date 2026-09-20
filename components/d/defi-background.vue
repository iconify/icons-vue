<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dswfyibqj"/><path class="ndmkwvbmu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:defi-background" /></template>
<style>
.dswfyibqj {
  fill: var(--svg-color--5fcade, #5fcade);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.ndmkwvbmu {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.21 8.42V5.053H20v3.369zm0 5.052v-3.368h8.422v3.368zm-4.21 0v-3.368h3.368v3.368zm4.21 5.476v-3.369H12v3.369z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

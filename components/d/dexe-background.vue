<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="bv1jyl_0a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dexe-background" /></template>
<style>
.bv1jyl_0a {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.432 6.608l-2.128 2.12a.43.43 0 0 1-.608 0l-2.124-2.12L6.528 6l4.448 4.436c.56.568 1.564.484 2.132-.08L17.472 6zM14 15.96v-3.008c0-.228.292-.548.528-.548h2.944L20 10.8h-6.176c-.784 0-1.424.764-1.424 1.56V18l1.6-2.044zM9.488 12.4H6.532L4 10.8h6.064c.784 0 1.536.652 1.536 1.452V18L10 15.952v-3c0-.232-.28-.552-.512-.552");
}

.ft5dv1b6b {
  fill: none;
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

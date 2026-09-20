<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="nm69djb4q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lgcy-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.nm69djb4q {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.36 4.01c.11.024.183.115.183.22v15.544a.224.224 0 0 1-.219.224a.23.23 0 0 1-.11-.023l-5.942-2.829a.22.22 0 0 1-.11-.288l5.942-12.724a.23.23 0 0 1 .26-.128zM6.18 15.758l4.904-5.26V5.257L6.181 15.752zm4.904-4.594l-5.338 5.714l5.338 2.545zm1.554-7.152a.224.224 0 0 0-.182.22v15.543c0 .078.04.15.11.192a.22.22 0 0 0 .219.01l5.941-2.83c.11-.05.16-.183.11-.288L12.895 4.134a.23.23 0 0 0-.26-.128zm5.179 11.746l-4.904-5.26V5.257l4.904 10.494zm-4.904-4.594l5.338 5.714l-5.338 2.545z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>

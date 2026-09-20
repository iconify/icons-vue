<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="v7s4c73oj"/><path class="o8qjn1bxi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arbitrum-nova-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o8qjn1bxi {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.55 6.4H8.086a.24.24 0 0 0-.226.163l-3.852 10.87c-.028.082.03.167.114.167h1.465a.24.24 0 0 0 .226-.163l3.852-10.87c.028-.081-.03-.167-.113-.167m1.783 4.555a.12.12 0 0 0-.226 0l-.76 2.144a.26.26 0 0 0 0 .17l1.477 4.168a.24.24 0 0 0 .226.163h1.465a.123.123 0 0 0 .114-.167zm3.736 2.099a.12.12 0 0 0 .226 0l2.298-6.488a.123.123 0 0 0-.113-.166h-1.465a.24.24 0 0 0-.226.163l-1.48 4.176a.25.25 0 0 0 0 .17zm-2.89-6.492a.24.24 0 0 0-.224-.162h-1.47a.24.24 0 0 0-.227.163l-3.851 10.87c-.029.082.03.167.113.167h1.465a.24.24 0 0 0 .227-.163l2.949-8.323a.06.06 0 0 1 .113 0l2.95 8.323a.24.24 0 0 0 .225.163h1.466a.124.124 0 0 0 .113-.166zm7.7-.162h-1.465a.24.24 0 0 0-.226.163l-2.68 7.562a.26.26 0 0 0 0 .17l.76 2.145a.12.12 0 0 0 .226 0l2.653-7.486l.846-2.388a.123.123 0 0 0-.114-.166");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v7s4c73oj {
  fill: var(--svg-color--ef8220, #ef8220);
  d: path("M24 0H0v24h24z");
}

</style>

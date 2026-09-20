<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="h3o4kgb5y"/><path class="v9q7a8u5r"/><path class="wrifqgb4i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:collab-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.h3o4kgb5y {
  fill: var(--svg-color--241d5e, #241d5e);
  d: path("M11.924 17.968c3.12 0 5.648-2.025 5.648-4.524S15.043 8.92 11.924 8.92c-3.12 0-5.648 2.026-5.648 4.524s2.529 4.524 5.648 4.524");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v9q7a8u5r {
  fill: var(--svg-color--f5c249, #f5c249);
  d: path("M19.72 11.728c-.132-1.36-.572-5.524-.58-5.68c-.008-.18-.268-.412-.268-.08c0 .236-.264 2.704-.264 4.632h-.464c-.868-2.112-3.16-3.5-5.892-3.592h-.528c-2.732.088-5.008 1.48-5.872 3.592h-.48c0-1.928-.24-4.4-.24-4.628c0-.336-.26-.104-.264.076c-.008.156-.448 4.32-.58 5.68c-.188.252-.292.56-.288.872c0 .504.336 1.04.744 1.04c.108.288.248.708.424.96h.664c.892 2.18 3.312 3.6 6.152 3.6s5.252-1.42 6.144-3.6h.692c.176-.252.332-.672.436-.96c.412 0 .744-.532.744-1.04c0-.312-.096-.62-.284-.872zm-7.732 6.092c-2.952 0-5.344-1.904-5.344-4.26c0-1.76 1.34-3.272 3.248-3.92l.348.716a.4.4 0 0 0 .148.18a.4.4 0 0 0 .224.064h2.76a.4.4 0 0 0 .224-.064a.4.4 0 0 0 .148-.18l.348-.712c1.904.652 3.236 2.16 3.236 3.92c0 2.352-2.392 4.256-5.34 4.256");
}

.wrifqgb4i {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M13.804 12.2a.6.6 0 0 0-.424.184a.66.66 0 0 0-.176.448v1.536c0 .168.064.328.176.448s.264.184.424.184a.6.6 0 0 0 .424-.184a.66.66 0 0 0 .176-.448v-1.536a.66.66 0 0 0-.176-.448a.58.58 0 0 0-.424-.184m-3.6 0a.6.6 0 0 0-.424.184a.66.66 0 0 0-.176.448v1.536c0 .168.064.328.176.448s.264.184.424.184s.312-.068.424-.184a.66.66 0 0 0 .176-.448v-1.536a.66.66 0 0 0-.176-.448a.58.58 0 0 0-.424-.184m1.8 4.4a.8.8 0 0 1-.8-.8h.26c0 .28.24.512.54.512c.296 0 .54-.232.54-.512h.26a.8.8 0 0 1-.8.8");
}

</style>

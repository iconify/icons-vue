<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h_4mjwb0v"/><path class="qgn5k9goy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fuse-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h_4mjwb0v {
  fill: var(--svg-color--b4f9b9, #b4f9b9);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qgn5k9goy {
  fill: var(--svg-color--000, #000);
  d: path("m9.33 5.5l2.56-1.47a.24.24 0 0 1 .235 0l6.75 3.876c.07.04.125.12.125.2v2.664a.22.22 0 0 1-.12.2l-2.55 1.47c-.16.095-.33-.02-.33-.2V9.85c0-.085-.085-.16-.155-.2L9.33 5.91a.235.235 0 0 1 0-.41M7.675 17.566l-2.555-1.47a.24.24 0 0 1-.12-.2v-7.75c0-.08.045-.16.12-.2l2.315-1.34a.24.24 0 0 1 .235 0l2.555 1.466c.16.095.16.32 0 .41L8.15 9.68c-.075.044-.15.12-.15.2v7.484c0 .18-.165.29-.325.2M19 15.89a.23.23 0 0 1-.12.205l-6.715 3.875a.24.24 0 0 1-.23 0L9.62 18.645a.24.24 0 0 1-.12-.2V15.5c0-.18.2-.295.35-.2l2.08 1.185c.07.04.16.04.235 0l6.48-3.74c.16-.09.35.025.35.2H19z");
}

</style>

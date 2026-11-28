<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="t2tey3b0u"><path class="nn5-k0uzo"/><path class="u0gkssb4i"/><path class="e6bv0xb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-trunk" /></template>
<style>
.e6bv0xb1z {
  d: path("M21.54 16.1h-2.97a2.64 2.64 0 0 0-2.66-2.63a2.6 2.6 0 0 0-1.87.78a2.6 2.6 0 0 0-.77 1.84h-2.98a5.63 5.63 0 1 1 11.27 0Z");
}

.nn5-k0uzo {
  d: path("M15.9 29.9v-2.98a11 11 0 0 0 6.05-1.81a10.86 10.86 0 0 0 1.64-16.65a10.9 10.9 0 0 0-16.72 1.68a11 11 0 0 0-1.82 5.95H2.02a13.7 13.7 0 0 1 2.34-7.67a13.89 13.89 0 1 1 19.27 19.14a14 14 0 0 1-7.72 2.34");
}

.t2tey3b0u {
  fill: var(--svg-color--fb6a5b, #fb6a5b);
}

.u0gkssb4i {
  d: path("M9.16 16.1H6.2a9.7 9.7 0 0 1 2.77-6.87a9.8 9.8 0 0 1 6.95-2.84v2.98a6.74 6.74 0 0 0-6.75 6.72");
}

</style>

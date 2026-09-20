<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rk_w2j-rj"/><path clip-rule="evenodd" class="lb7t2mb0u"/><path class="g9kl0pbgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fnox" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g9kl0pbgx {
  fill: var(--svg-color--0a0e1a, #0a0e1a);
  d: path("m10.459 13.083l2.333.875l-1.458 1.167zm11.083 0l-2.333.875l1.458 1.167z");
}

.lb7t2mb0u {
  fill: var(--svg-color--d4af37, #d4af37);
  fill-rule: evenodd;
  d: path("M16 2.656c7.37 0 13.343 5.975 13.344 13.344c0 7.37-5.975 13.343-13.344 13.343C8.63 29.343 2.656 23.37 2.656 16S8.63 2.656 16 2.656M23.292 16L16 26.209L8.708 16l-.874-9.615A12.59 12.59 0 0 0 3.386 16c0 6.967 5.647 12.614 12.614 12.614S28.614 22.967 28.615 16c0-3.852-1.728-7.301-4.45-9.615zM16 11.783a2.48 2.48 0 0 0-2.415 3.04a2.5 2.5 0 0 0 .738 1.264l-.656 5.747h4.666l-.656-5.747a2.478 2.478 0 0 0-.278-3.872A2.5 2.5 0 0 0 16 11.783m0-8.397c-3.112 0-5.96 1.126-8.16 2.994l5.535 3.495h5.25l5.534-3.495A12.57 12.57 0 0 0 16 3.385");
}

.rk_w2j-rj {
  fill: var(--svg-color--0a0e1a, #0a0e1a);
  d: path("M16 30c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14");
}

</style>

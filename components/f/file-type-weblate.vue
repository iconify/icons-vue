<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<linearGradient id="SVGdr4zccAc" x1=".4" x2="98.81" y1="55.26" y2="55.26" gradientTransform="matrix(.14 0 0 .14 1.94 5.58)" gradientUnits="userSpaceOnUse"><stop class="f9jnagbbl"/><stop offset="1" class="qthc_55up"/></linearGradient><linearGradient id="SVGktUkRwfn" x1="201.82" x2="103.58" y1="57.65" y2="57.65" gradientTransform="matrix(.14 0 0 .14 1.94 5.58)" gradientUnits="userSpaceOnUse"><stop class="tnb5-4jvo"/><stop offset="1" class="qthc_55up"/></linearGradient><path fill="url(#SVGdr4zccAc)" class="vkc3_8b9x"/><path fill="url(#SVGktUkRwfn)" class="o45ehxtrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-weblate" /></template>
<style>
.f9jnagbbl {
  stop-color: var(--svg-color--00d2e6, #00d2e6);
}

.o45ehxtrn {
  d: path("M9.97 13.3v-.1c.02-2.65 1.11-5.36 3.3-6.76a5.15 5.15 0 0 1 2.73-.8V9.8a.8.8 0 0 0-.34.06c-.62.26-1.01.94-1.26 1.6c-.2.59-.3 1.22-.3 1.83v.08l-.01.1c.02 1.57.31 3.16.94 4.6c.7 1.63 1.8 3.12 3.37 3.8c1.18.52 2.49.4 3.56-.21a7.33 7.33 0 0 0 2.92-3.51c1.3-2.97 1.33-6.6.03-9.64c1.27-.66 1.27-1.97 1.27-1.97s1.18.85 2.52.32a16.52 16.52 0 0 1-.14 13.17c-1.1 2.4-2.88 4.5-5.2 5.59a8.1 8.1 0 0 1-6.6.08a10.36 10.36 0 0 1-4.47-3.98a15.74 15.74 0 0 1-2.33-8.43z");
}

.qthc_55up {
  stop-color: var(--svg-color--2eccaa, #2eccaa);
}

.tnb5-4jvo {
  stop-color: var(--svg-color--1fa385, #1fa385);
}

.vkc3_8b9x {
  d: path("M19.94 21.36c-.41 0-.82-.09-1.2-.25a5.25 5.25 0 0 1-2.25-2.05a12.14 12.14 0 0 0 1.41-5.67v-.09c0-.61-.1-1.24-.3-1.82c-.25-.67-.64-1.35-1.26-1.6A.8.8 0 0 0 16 9.8c-.77-1.46-.8-2.85 0-4.18h.05c.95.01 1.88.3 2.69.82c2.18 1.39 3.28 4.1 3.3 6.76v.1h.01c0 2.8-.68 5.65-2.1 8.05zm-4.85 4.41a8.1 8.1 0 0 1-6.44-.14c-2.33-1.08-4.11-3.19-5.2-5.59A16.53 16.53 0 0 1 3.3 6.87c1.34.53 2.52-.32 2.52-.32s0 1.31 1.27 1.97a12.38 12.38 0 0 0 .03 9.64a7.33 7.33 0 0 0 2.92 3.51c.47.27 1 .44 1.53.5v.02c.95 1.47 2.15 2.7 3.52 3.58");
}

</style>

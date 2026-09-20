<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG9MunNeKt" x1="24.11" x2="4.48" y1="808.88" y2="835.23" gradientTransform="translate(0 -807.89)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="iumhsbc7c"/><stop offset=".5" class="utw4-0bqv"/><stop offset="1" class="csq6hccpd"/></linearGradient></defs><path fill="url(#SVG9MunNeKt)" class="nkz6w4etv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-doppler" /></template>
<style>
.csq6hccpd {
  stop-color: var(--svg-color--516ff7, #516ff7);
}

.iumhsbc7c {
  stop-color: var(--svg-color--409ff8, #409ff8);
}

.nkz6w4etv {
  fill-rule: evenodd;
  d: path("M2.59 2a.27.27 0 0 0-.23.43l5 7.8a2.25 2.25 0 0 0 1.88 1H16c2.47 0 4 2.18 4 4.62s-1.65 4.61-4 4.61H8.78a.75.75 0 0 0-.74.75H8v7.8a.75.75 0 0 0 .75.74H18c7.94 0 11.91-7.54 11.91-13.9S26 2 18 2Zm3.28 18.56h-1.8a2.17 2.17 0 0 0-2 2.32v6.74a.2.2 0 0 0 .18.21h1.8a2.19 2.19 0 0 0 2-2.32v-6.74a.2.2 0 0 0-.19-.21Z");
}

.utw4-0bqv {
  stop-color: var(--svg-color--1673ff, #1673ff);
}

</style>

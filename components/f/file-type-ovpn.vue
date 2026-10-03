<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d2f4n4b1p"/><path class="pi20xyb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ovpn" /></template>
<style>
.d2f4n4b1p {
  fill: var(--svg-color--ff9100, #ff9100);
  d: path("M16 2a14 14 0 0 0-7 26.1l3.14-5.44A7.69 7.69 0 0 1 16 8.3a7.7 7.7 0 0 1 3.86 14.36L23 28.1A13.99 13.99 0 0 0 16 2");
}

.pi20xyb5u {
  fill: var(--svg-color--1a237e, #1a237e);
  d: path("M20.2 16a4.2 4.2 0 1 0-5.7 3.92l-1.8 9.67a14 14 0 0 0 6.6 0l-1.8-9.67A4.2 4.2 0 0 0 20.2 16");
}

</style>

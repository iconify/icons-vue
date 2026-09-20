<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d5hkhbues"/><path class="n0sheabld"/><circle class="xn_m8eb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-apib" /></template>
<style>
.d5hkhbues {
  fill: var(--svg-color--a0b3c1, #a0b3c1);
  d: path("m18.053 12.267l4.76 7.467l.373.56l1.12-.653l-.373-.56l-4.76-7.467l-.373-.654l-1.12.653zm-5.227-.747l-4.76 7.467l-.373.56l1.12.653l.373-.467l4.76-7.467l.373-.56l-1.119-.746z");
}

.n0sheabld {
  fill: var(--svg-color--a0b3c1, #a0b3c1);
  d: path("M16 13.107a4.98 4.98 0 0 0 4.947-4.947A5.06 5.06 0 0 0 16 3.12a4.98 4.98 0 0 0-4.947 4.947A5.06 5.06 0 0 0 16 13.107m0-1.307a3.644 3.644 0 0 1-3.64-3.64a3.64 3.64 0 1 1 7.28 0A3.644 3.644 0 0 1 16 11.8m9.053 17.08a4.947 4.947 0 1 0-4.947-4.947a4.98 4.98 0 0 0 4.947 4.947m0-1.307a3.644 3.644 0 0 1-3.64-3.64a3.64 3.64 0 1 1 7.28 0a3.644 3.644 0 0 1-3.64 3.64M6.947 28.88a4.947 4.947 0 1 0 0-9.893a4.947 4.947 0 1 0 0 9.893m0-1.307a3.644 3.644 0 0 1-3.64-3.64a3.706 3.706 0 0 1 3.64-3.64a3.706 3.706 0 0 1 3.64 3.64a3.644 3.644 0 0 1-3.64 3.64");
}

.xn_m8eb6r {
  cx: 6.947px;
  cy: 23.933px;
  r: 1.68px;
  fill: var(--svg-color--5e9cff, #5e9cff);
}

</style>

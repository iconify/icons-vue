<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfnw7ybgu"/><path class="dnnm48bsv"/><path class="z0w0zkb7y"/><path class="awv1l0b_p"/><path class="wgej8o75l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-common-opened" /></template>
<style>
.awv1l0b_p {
  fill: var(--svg-color--d1d1d1, #d1d1d1);
  d: path("M17.507 22.5a6.01 6.01 0 0 0 4.686 5.85a7.49 7.49 0 0 0 0-11.7a6.01 6.01 0 0 0-4.686 5.85");
}

.dnnm48bsv {
  fill: var(--svg-color--a1aeb9, #a1aeb9);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2Z");
}

.rfnw7ybgu {
  fill: var(--svg-color--a1aeb9, #a1aeb9);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.wgej8o75l {
  fill: var(--svg-color--d1d1d1, #d1d1d1);
  d: path("M16.007 22.5a7.51 7.51 0 0 1 4.5-6.87a7.5 7.5 0 1 0 0 13.74a7.51 7.51 0 0 1-4.5-6.87");
}

.z0w0zkb7y {
  fill: var(--svg-color--d1d1d1, #d1d1d1);
  d: path("M23.507 15a7.45 7.45 0 0 0-3 .63a7.5 7.5 0 0 1 1.684 1.02a6 6 0 1 1 0 11.7a7.5 7.5 0 0 1-1.684 1.02a7.5 7.5 0 1 0 3-14.371Z");
}

</style>

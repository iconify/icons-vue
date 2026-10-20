<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n5oyzf-wn"/><path class="v5rxlbb5d"/><path class="g7v6cko7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-seedkit" /></template>
<style>
.g7v6cko7b {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.94 21.21c0-.16.13-.29.29-.29h3.48a3.776 3.776 0 0 1 3.78 3.77c0 2.08-1.69 3.76-3.78 3.76c-2.08 0-3.77-1.68-3.77-3.76zm0-1.41c0 .16.13.29.29.29h3.48a3.776 3.776 0 0 0 3.78-3.77c0-2.08-1.69-3.76-3.78-3.76c-2.08 0-3.77 1.68-3.77 3.76zm-.84 1.41a.29.29 0 0 0-.29-.29h-3.48a3.77 3.77 0 0 0-3.77 3.77a3.765 3.765 0 0 0 3.77 3.76a3.765 3.765 0 0 0 3.77-3.76zm0-1.41a.29.29 0 0 1-.29.29h-3.48a3.77 3.77 0 0 1-3.77-3.77a3.765 3.765 0 0 1 3.77-3.76a3.765 3.765 0 0 1 3.77 3.76z");
}

.n5oyzf-wn {
  fill: var(--svg-color--2d2e76, #2d2e76);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.v5rxlbb5d {
  fill: var(--svg-color--4f51e5, #4f51e5);
  d: path("M10.05 16.74c0-2.34 0-3.51.45-4.41a4.2 4.2 0 0 1 1.84-1.83c.89-.45 2.07-.45 4.41-.45h7.54c2.35 0 3.53 0 4.42.45a4.2 4.2 0 0 1 1.83 1.83c.46.9.46 2.07.46 4.41v7.53c0 2.34 0 3.51-.46 4.41a4.2 4.2 0 0 1-1.83 1.83c-.89.45-2.07.45-4.42.45h-7.54c-2.34 0-3.52 0-4.41-.45a4.2 4.2 0 0 1-1.84-1.83c-.45-.9-.45-2.07-.45-4.41z");
}

</style>

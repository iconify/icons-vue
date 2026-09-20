<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG8cslKeZN" x1="16" x2="16" y1="3" y2="29" gradientUnits="userSpaceOnUse"><stop offset="0" class="c7ihwacvh"/><stop offset="1" class="h-kbkc4su"/></linearGradient></defs><path fill="url(#SVG8cslKeZN)" class="nkkc85-iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-processinglang" /></template>
<style>
.c7ihwacvh {
  stop-color: var(--svg-color--1c4c70, #1c4c70);
}

.h-kbkc4su {
  stop-color: var(--svg-color--0c2b42, #0c2b42);
}

.nkkc85-iu {
  d: path("M15.922 19.962a13 13 0 0 1-1.647-.077v5.552a28 28 0 0 1 3.332.461V29H5.968v-3.1a28 28 0 0 1 3.332-.462V6.715a28 28 0 0 1-3.331-.46v-3.1h2.986C10.18 3.153 13.549 3 16.23 3c6.318 0 9.8 2.948 9.8 8c.001 5.018-3.83 8.962-10.108 8.962M16 7.058c-.613 0-1.149 0-1.723.038v8.615a10 10 0 0 0 1.455.115c3.025-.038 5.13-1.723 5.13-4.519c0-2.607-1.455-4.249-4.862-4.249");
}

</style>

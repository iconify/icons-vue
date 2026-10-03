<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rrvy06cly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-hurl" /></template>
<style>
.rrvy06cly {
  fill: var(--svg-color--ff0288, #ff0288);
  d: path("M3.11 8.67h20.16V4.36L30 10.64l-6.74 6.28v-4.06H3.12zM28.9 19.4H8.73v-4.32L2 21.36l6.74 6.28V23.6h20.15z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rvllrvb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cheader" /></template>
<style>
.rvllrvb7o {
  fill: var(--svg-color--005f91, #005f91);
  d: path("M8.329 29V3h3.192v9.329a7.13 7.13 0 0 1 5.64-2.589a7.6 7.6 0 0 1 3.636.825a4.84 4.84 0 0 1 2.208 2.279a10.5 10.5 0 0 1 .665 4.221V29h-3.192V17.064a4.93 4.93 0 0 0-1.038-3.485a3.86 3.86 0 0 0-2.935-1.091a5.2 5.2 0 0 0-2.669.736a4.16 4.16 0 0 0-1.782 2a9.2 9.2 0 0 0-.532 3.476V29Z");
}

</style>

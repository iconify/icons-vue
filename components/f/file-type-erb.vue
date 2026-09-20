<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pcrg7_beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-erb" /></template>
<style>
.pcrg7_beg {
  fill: var(--svg-color--921a1e, #921a1e);
  d: path("M7.25 24.75h17.5L12.5 12.5l-5.25 5.25ZM2 30h28V2H16L2 16Zm25.375-2.625H4.625v-10.5l12.25-12.25h10.5Z");
}

</style>

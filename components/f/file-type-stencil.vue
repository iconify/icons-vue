<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qg3ru238x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-stencil" /></template>
<style>
.qg3ru238x {
  fill: var(--svg-color--7b79ff, #7b79ff);
  d: path("M30 12.849H7.83L2 19.151h22.17Zm-15.217-7.47h10.751l-5.806 6.3H8.968Zm-2.373 14.94H23.2l-5.833 6.3H6.634Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j334wwbbl"/><path class="yqkvqtb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-purescript" /></template>
<style>
.j334wwbbl {
  fill: var(--svg-color--16171b, #16171b);
  d: path("M2.02 2.02h27.96v27.96H2.02z");
}

.yqkvqtb7p {
  fill: var(--svg-color--fff, #fff);
  d: path("m21.15 21.36l-1.91-1.78h-8.39l1.91 1.78zm-8.39-6.25l-1.9 1.78h8.38l1.9-1.78zm8.39-2.69l-1.91-1.78h-8.39l1.91 1.78zM9.97 14.2l-1.26-1.26l-4.68 4.67a.9.9 0 0 0 0 1.26l4.68 4.68l1.26-1.26l-4.05-4.05Zm18-1.05L23.3 8.46l-1.26 1.26l4.04 4.05l-4.04 4.04l1.26 1.26l4.68-4.67a.9.9 0 0 0 0-1.26");
}

</style>

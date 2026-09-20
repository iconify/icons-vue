<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="udx-gdbie"/><path class="pn36f1z8c"/><path class="u6ct81g1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vsix" /></template>
<style>
.pn36f1z8c {
  fill: var(--svg-color--cfcfcf, #cfcfcf);
  d: path("M10 16v6h12V10H10Z");
}

.u6ct81g1c {
  fill: var(--svg-color--cfcfcf, #cfcfcf);
  d: path("M24 20.5V24h-7v6h13V17h-6Z");
}

.udx-gdbie {
  fill: var(--svg-color--cfcfcf, #cfcfcf);
  d: path("M2 16v14h13v-6H8V8h7V2H2ZM17 5v3h4V6h5v5h-2v4h6V2H17Z");
}

</style>

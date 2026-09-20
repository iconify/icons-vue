<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qdkg1gbth"/><path class="kbddf3bpw"/><path class="l9bh7yenp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-vsix" /></template>
<style>
.kbddf3bpw {
  fill: var(--svg-color--424242, #424242);
  d: path("M10 16v6h12V10H10Z");
}

.l9bh7yenp {
  fill: var(--svg-color--424242, #424242);
  d: path("M24 20.5V24h-7v6h13V17h-6Z");
}

.qdkg1gbth {
  fill: var(--svg-color--424242, #424242);
  d: path("M2 16v14h13v-6H8V8h7V2H2ZM17 5v3h4V6h5v5h-2v4h6V2H17Z");
}

</style>

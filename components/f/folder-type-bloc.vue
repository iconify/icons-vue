<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qc1vmsbgn"/><path class="ntuumre2a"/><path class="k8qxfilja"/><path class="imk-hfbnk"/><path class="g98vaobit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-bloc" /></template>
<style>
.g98vaobit {
  fill: var(--svg-color--00d3b9, #00d3b9);
  d: path("M22.429 28.857V21l6.804-3.929v7.858z");
}

.imk-hfbnk {
  fill: var(--svg-color--82eddf, #82eddf);
  d: path("M15.624 17.071v7.858l6.805 3.928V21z");
}

.k8qxfilja {
  fill: var(--svg-color--0084c1, #0084c1);
  d: path("M15.624 17.071L22.429 21l6.804-3.929l-6.804-3.928z");
}

.ntuumre2a {
  d: path("m31 26l-8.571 5l-8.572-5V16l8.572-5L31 16z");
}

.qc1vmsbgn {
  fill: var(--svg-color--55a3bf, #55a3bf);
  d: path("M27.417 5.5H18.19l-2.083 4.2H4.5v16.8h25v-21Zm0 4.2h-8.135l1.091-2.1h7.044Z");
}

</style>

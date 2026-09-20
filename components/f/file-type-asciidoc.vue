<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c60ho2btg"/><path class="uv-1yhtet"/><path class="zu4atvb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-asciidoc" /></template>
<style>
.c60ho2btg {
  fill: var(--svg-color--e40046, #e40046);
  d: path("M30 30H2V2h28Z");
}

.uv-1yhtet {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.731 24.83a.59.59 0 0 1-.763-.337L16.724 9.269L13.93 15.99h1.833a.59.59 0 0 1-.024 1.18H8.9a.59.59 0 0 1 .024-1.18h3.727v-.013L16.184 7.5a.59.59 0 0 1 .533-.363a.59.59 0 0 1 .557.366l6.785 16.546l.009.021a.59.59 0 0 1-.337.76");
}

.zu4atvb_l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.516 18.791H7.679a.59.59 0 0 0-.024 1.18H11l-1.691 4.072a.59.59 0 0 0 1.085.464v-.011l1.875-4.509l.005-.016h2.215a.59.59 0 0 0 .023-1.18Z");
}

</style>

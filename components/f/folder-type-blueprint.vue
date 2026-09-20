<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVG4KxUuelT" cx="19.64" cy="19.72" r="15.24" gradientUnits="userSpaceOnUse"><stop offset="0" class="dcn4qobec"/><stop offset=".857" class="tp4o_uq6c"/><stop offset=".929" class="u8nsubbcj"/></radialGradient></defs><path class="fyrr5sbey"/><path fill="url(#SVG4KxUuelT)" class="w3_nihb2d"/><g class="s_e6o76-f"><path class="qcmalobfe"/><path class="x-c3yuzdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-blueprint" /></template>
<style>
.dcn4qobec {
  stop-color: var(--svg-color--138fce, #138fce);
}

.fyrr5sbey {
  fill: var(--svg-color--557ebf, #557ebf);
  d: path("M27.9 6h-9.8l-2 4H5v17h25V6Zm.1 4h-7.8l1-2H28Z");
}

.qcmalobfe {
  d: path("M13.679 11h.357v20h-.357zm2.857 0h.357v20h-.357zm2.857 0h.357v20h-.357zm2.857 0h.357v20h-.357zm2.857 0h.357v20h-.357zm2.857 0h.357v20h-.357z");
}

.s_e6o76-f {
  fill: var(--svg-color--fff, #fff);
  opacity: var(--svg-opacity--0-23, 0.23);
}

.tp4o_uq6c {
  stop-color: var(--svg-color--385eaa, #385eaa);
}

.u8nsubbcj {
  stop-color: var(--svg-color--3265af, #3265af);
}

.w3_nihb2d {
  d: path("M11 11h20v20H11z");
}

.x-c3yuzdl {
  d: path("M11 13.679h20v.357H11zm0 2.857h20v.357H11zm0 2.857h20v.357H11zm0 2.857h20v.357H11zm0 2.857h20v.357H11zm0 2.857h20v.357H11z");
}

</style>

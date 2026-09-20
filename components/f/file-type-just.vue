<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="lmh4whbrs"/><ellipse class="m96ir8bsl"/><ellipse class="ebyf81b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-just" /></template>
<style>
.ebyf81b9p {
  cx: 16px;
  cy: 23.3px;
  fill: var(--svg-color--fff, #fff);
  rx: 3.8px;
  ry: 3.9px;
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.m96ir8bsl {
  cx: 16px;
  cy: 8.7px;
  fill: var(--svg-color--fff, #fff);
  rx: 3.8px;
  ry: 3.9px;
}

</style>

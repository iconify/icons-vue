<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="i3pxi5dqx"/><path class="iwy9kzbma"/><path class="zml66qbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-drawio" /></template>
<style>
.i3pxi5dqx {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  fill: var(--svg-color--f08705, #f08705);
  rx: 1.12px;
}

.iwy9kzbma {
  fill: var(--svg-color--df6c0c, #df6c0c);
  fill-rule: evenodd;
  d: path("m16.861 9.168l3.02-3.187L30 16.094V28.88A1.12 1.12 0 0 1 28.88 30H11.316l-5.385-5.407Z");
}

.zml66qbaf {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.24 17.96h-3.294l-3.071-5.32h.2a1.12 1.12 0 0 0 1.12-1.12V6.76a1.12 1.12 0 0 0-1.12-1.12H12.92a1.12 1.12 0 0 0-1.12 1.12v4.76a1.12 1.12 0 0 0 1.12 1.12h.205l-3.071 5.32H6.76a1.12 1.12 0 0 0-1.12 1.12v4.76a1.12 1.12 0 0 0 1.12 1.12h6.16a1.12 1.12 0 0 0 1.12-1.12v-4.76a1.12 1.12 0 0 0-1.12-1.12h-.927l3.072-5.32h1.87l3.071 5.32h-.926a1.12 1.12 0 0 0-1.12 1.12v4.76a1.12 1.12 0 0 0 1.12 1.12h6.16a1.12 1.12 0 0 0 1.12-1.12v-4.76a1.12 1.12 0 0 0-1.12-1.12");
}

</style>

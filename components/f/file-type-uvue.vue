<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="klp2w1ufy"/><path class="wjpk5etqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-uvue" /></template>
<style>
.klp2w1ufy {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--24983a, #24983a);
}

.wjpk5etqb {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.5 10.01v13.47H9.51V10H12v11h8V10.01z");
}

</style>

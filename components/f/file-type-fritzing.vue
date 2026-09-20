<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="gi_w29t_a"/><g transform="translate(.038 .001)" class="dlrjxpbzv"><path class="hcigarxix"/><circle class="lvr-91x8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fritzing" /></template>
<style>
.dlrjxpbzv {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gi_w29t_a {
  width: 29.772px;
  height: 29.772px;
  x: 1.114px;
  y: 1.114px;
  fill: var(--svg-color--d33020, #d33020);
  rx: 6.6px;
  ry: 6.6px;
}

.hcigarxix {
  stroke-width: var(--svg-stroke-width--2-986px, 2.986px);
  d: path("M20.875 6.036s-1.74-.032-4.602.038c-.884.02-1.96 1.079-1.984 1.727c-.03.872.037 12.488.037 12.488m-3.276-7.78h7.805");
}

.lvr-91x8r {
  cx: 14.404px;
  cy: 23.774px;
  r: 2.573px;
  stroke-width: var(--svg-stroke-width--2-23px, 2.23px);
}

</style>

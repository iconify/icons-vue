<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":8.467,"height":8.467};
const content = `<path class="ckddz7_qh"/><path class="a yj0xn5bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-tsdoc" /></template>
<style>
.ckddz7_qh {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: bevel;
  stroke-width: var(--svg-stroke-width--0-28px, 0.28px);
  d: path("M3.865 3.873h3.027V6.9H3.865z");
}

.yj0xn5bsx {
  fill: var(--svg-color--108938, #108938);
  d: path("M7.68.53H.786A.257.257 0 0 0 .53.785V7.68a.257.257 0 0 0 .257.258H7.68a.257.257 0 0 0 .258-.258V.786A.257.257 0 0 0 7.68.53m-.669 5.345l-.378.652l-.954-.675l.11 1.16h-.792l.106-1.16l-.95.675l-.383-.652l1.064-.484l-1.064-.484l.383-.653l.95.675l-.106-1.159h.791l-.11 1.16l.955-.676l.378.653l-1.06.484z");
}

</style>

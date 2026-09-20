<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGDM0jtdZw" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop offset="0" class="l54enn66f"/><stop offset="1" class="x3r8acckm"/></linearGradient></defs><rect fill="url(#SVGDM0jtdZw)" class="f84r8k3nc"/><path class="z7ezd-b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-stata" /></template>
<style>
.f84r8k3nc {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  rx: 1.556px;
  ry: 1.556px;
}

.l54enn66f {
  stop-color: var(--svg-color--8aa7c0, #8aa7c0);
}

.x3r8acckm {
  stop-color: var(--svg-color--3c6e8f, #3c6e8f);
}

.z7ezd-b7n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.171 6.015h5.756v5.756h-5.756zm7.155 0h5.756v5.756h-5.756zm0 7.156h5.756v5.756h-5.756zm-7.155 0h5.756v5.756h-5.756zm-7.156 0h5.756v5.756H6.015zm0 7.155h5.756v5.756H6.015zm7.156 0h5.756v5.756h-5.756z");
}

</style>

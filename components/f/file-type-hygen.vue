<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="rews4rbix"/><path class="zleqtaczw"/><path class="e5snweb_b"/><path class="r2r3b1c3u"/><path class="oxpnpfmqa"/><path class="hka0d3-um"/><path class="hy61amayk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-hygen" /></template>
<style>
.e5snweb_b {
  fill: var(--svg-color--bcfe25, #bcfe25);
  d: path("M18.771 24.651h3.084v1.928h-3.084z");
}

.hka0d3-um {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.169 30v-7.663a6.167 6.167 0 0 1 6.168-6.168H30Z");
}

.hy61amayk {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M9.133 6.819h9.446v1.928H9.133zm10.409 0h3.373v1.928h-3.373zm-13.108 0h1.735v1.928H6.434zm2.699 14.94h6.747v1.928H9.133zm-2.699 0h1.735v1.928H6.434zm5.59 2.892h3.855v1.928h-3.855zm-5.59 0h4.627v1.928H6.434zM11.735 10h5.301v1.928h-5.301zm-5.301 0h4.241v1.928H6.434zm0 3.277h6.458v1.928H6.434z");
}

.oxpnpfmqa {
  fill: var(--svg-color--c9c9c9, #c9c9c9);
  fill-rule: evenodd;
  d: path("M8.169 2h15.614a6.17 6.17 0 0 1 6.169 6.169v7.807L15.976 29.952H8.169A6.17 6.17 0 0 1 2 23.783V8.169A6.17 6.17 0 0 1 8.169 2");
}

.r2r3b1c3u {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.434 24.651h1.157v1.928h-1.157z");
}

.rews4rbix {
  width: 27.566px;
  height: 27.566px;
  x: 2.096px;
  y: 2.096px;
  fill: var(--svg-color--f722b1, #f722b1);
  rx: 6.169px;
}

.zleqtaczw {
  fill: var(--svg-color--fff06c, #fff06c);
  d: path("M18.771 21.759h6.554v1.928h-6.554z");
}

</style>

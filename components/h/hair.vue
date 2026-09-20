<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="isef2ovgj"/><path class="jou6xdmhc"/><path class="qpvs1hb2z"/><path class="uo8ci400b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hair" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.isef2ovgj {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 20.47a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94m0 .53a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.jou6xdmhc {
  fill: var(--svg-color--000, #000);
  d: path("M11.47 8.294H9.353l.529.53v5.823l-.53.53h2.118l-.53-.53V8.824z");
}

.qpvs1hb2z {
  fill: var(--svg-color--3fd0c8, #3fd0c8);
  d: path("M6.706 13.588V12.21c.608-.678 1.747-1.848 2.784-1.668c.64.106.9.885.837 1.451c.212-.212.423-.434.672-.603c.185-.133.567-.334.974-.127c.376.185.53.513.598.767l.149-.09c.338-.201.847-.471 1.397-.471h3.177v1.059h-3.177c-.392 0-.757.26-1.074.46c-.233.149-.487.334-.779.334c-.19 0-.36-.08-.476-.217c-.201-.233-.159-.53-.238-.81c-.334.26-.583.603-.932.847c-.185.127-.567.328-.974.122a.9.9 0 0 1-.334-.27c-.344-.477.127-.927-.069-1.382c-.92.328-1.905 1.276-2.535 1.975");
}

.uo8ci400b {
  fill: var(--svg-color--000, #000);
  d: path("M14.647 8.294h-2.118l.53.53v5.823l-.53.53h2.118l-.53-.53V8.824z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="yc9c7lypi"/><path clip-rule="evenodd" class="xdtch8b5h"/><path class="qm5_v_rrj"/><g class="wma6sjbrm"><circle class="snnb9r0td"/><circle class="xmljydeij"/><circle class="vnslug0hy"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-quarkdown" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qm5_v_rrj {
  stroke: var(--svg-color--212d2d, #212d2d);
  stroke-width: var(--svg-stroke-width--1-39px, 1.39px);
  d: path("M14.87 16.34s3.75 1.65 6.63 3.92c.16.12.4.05.45-.14c.96-3.16 2.11-6.56 2.11-6.56");
}

.snnb9r0td {
  cx: 8.48px;
  cy: 15.09px;
  r: 0.98px;
}

.vnslug0hy {
  cx: 10.85px;
  cy: 9.66px;
  r: 0.56px;
}

.wma6sjbrm {
  fill: var(--svg-color--212d2d, #212d2d);
  stroke-width: var(--svg-stroke-width--0-28px, 0.28px);
}

.xdtch8b5h {
  fill: var(--svg-color--212d2d, #212d2d);
  fill-rule: evenodd;
  d: path("M20.83 20.02a43 43 0 0 0-1.63-5.1a35 35 0 0 0-4.81-8.9a9 9 0 0 0-2.12-2.07a2 2 0 0 0-.62-.27c-.05.06-.16.23-.26.61q-.19.66-.21 1.76q-.88.43-1.66 1c-.12-2.65.37-4.5 1.53-4.95c2.4-.92 6.75 4.55 9.71 12.22c.74 1.9 1.32 3.77 1.74 5.51a1.2 1.2 0 0 0-1.17-.19q-.31.13-.5.38m.49 2.32q.22 1.3.3 2.4q.1 1.98-.18 2.97c-.11.38-.22.55-.27.61a2 2 0 0 1-.61-.27a8 8 0 0 1-1.64-1.5a11 11 0 0 1-1.88.35c1.8 2.29 3.52 3.47 4.74 3c1.54-.6 1.9-3.69 1.18-7.86q-.2.3-.54.44a1.2 1.2 0 0 1-1.1-.14M11.6 3.67");
}

.xmljydeij {
  cx: 9.45px;
  cy: 11.89px;
  r: 0.84px;
}

.yc9c7lypi {
  fill: var(--svg-color--212d2d, #212d2d);
  fill-rule: evenodd;
  d: path("M20.53 25.98a11 11 0 0 1-15.46-8.73a11 11 0 0 1 6.1-11.2l-.05.97a10.17 10.17 0 0 0 9.38 18.05v.03zm3.7-2.73a11 11 0 0 0-7.35-18.27l.66.91a10.17 10.17 0 0 1 6.52 16.26q.1.56.17 1.1");
}

</style>

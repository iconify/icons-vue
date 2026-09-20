<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mvr4pf2-u"/><circle class="b-nb_ibvm"/><circle class="z988kebku"/><circle class="y7mrt5bze"/><path class="fa9yvvhjc"/><path class="kf2xs17lp"/><path class="h03lg2b0s"/><path class="urt0760lp"/><path class="qewqj1bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fantasticon" /></template>
<style>
.b-nb_ibvm {
  cx: 15.92px;
  cy: 8.75px;
  r: 1.87px;
  fill: var(--svg-color--21ffc9, #21ffc9);
}

.fa9yvvhjc {
  fill: var(--svg-color--f37, #f37);
  d: path("M6.51 6.87h3.75v3.75H6.51z");
}

.h03lg2b0s {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.59 21.42h3.75v3.75h-3.75zm-7.79-3.56l2.13-3.75l2.14 3.75Z");
}

.kf2xs17lp {
  fill: var(--svg-color--21ffc9, #21ffc9);
  d: path("M21.59 14.15h3.75v3.75h-3.75z");
}

.mvr4pf2-u {
  d: path("M30 3.27A1.27 1.27 0 0 0 28.73 2H3.27A1.27 1.27 0 0 0 2 3.27v25.46A1.27 1.27 0 0 0 3.27 30h25.46A1.27 1.27 0 0 0 30 28.73z");
}

.qewqj1bct {
  fill: var(--svg-color--21ffc9, #21ffc9);
  d: path("m6.25 25.17l2.13-3.75l2.14 3.75Z");
}

.urt0760lp {
  fill: var(--svg-color--f37, #f37);
  d: path("m21.34 10.62l2.13-3.75l2.13 3.75Z");
}

.y7mrt5bze {
  cx: 15.92px;
  cy: 23.3px;
  r: 1.87px;
  fill: var(--svg-color--f37, #f37);
}

.z988kebku {
  cx: 8.38px;
  cy: 16px;
  r: 1.87px;
  fill: var(--svg-color--fff, #fff);
}

</style>

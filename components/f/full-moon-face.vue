<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="pyqr-0b4t"/><g class="cm1o77xew"><circle class="yj94e4bca"/><circle class="h43cugwhq"/><circle class="iptj1fskr"/><circle class="q-ob0owtj"/><circle class="ls1yo1gbk"/><circle class="hg7lxphel"/><circle class="r_w28qzwq"/><circle class="lvjz7-bia"/><circle class="x2stddcav"/><circle class="hqsly9zby"/><circle class="fx05f8yqh"/><circle class="sek9l58ct"/><path class="vtqnjlbta"/></g><g class="a0bxpwzvt"><path class="jtccn7b7f"/><path class="oibxpzeoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:full-moon-face" /></template>
<style>
.a0bxpwzvt {
  fill: var(--svg-color--827717, #827717);
}

.cm1o77xew {
  fill: var(--svg-color--f4dc9f, #f4dc9f);
}

.fx05f8yqh {
  cx: 15px;
  cy: 15.7px;
  r: 2px;
}

.h43cugwhq {
  cx: 18.1px;
  cy: 39px;
  r: 6px;
}

.hg7lxphel {
  cx: 12.1px;
  cy: 25.9px;
  r: 4px;
}

.hqsly9zby {
  cx: 25px;
  cy: 29.9px;
  r: 3px;
}

.iptj1fskr {
  cx: 24.2px;
  cy: 50px;
  r: 9px;
}

.jtccn7b7f {
  d: path("M37 39c-3.5 4.9-11.3 4.8-9.8-3.7c.6-3.3 2.2-13 2.2-13v10.6c0 7.6 2.1 7.3 7.6 6.1");
}

.ls1yo1gbk {
  cx: 37px;
  cy: 18.2px;
  r: 4px;
}

.lvjz7-bia {
  cx: 8.1px;
  cy: 39px;
  r: 2px;
}

.oibxpzeoc {
  d: path("M42.8 43.9c-7 4.8-14.7 4.8-21.6 0c-.8-.6-1.6.4-1 1.4c2.1 3.5 6.4 6.6 11.8 6.6s9.7-3.1 11.8-6.6c.6-1-.2-2-1-1.4m-4.4-19.2c3.7 7 11.2 7 14.9 0c.2-.4-.3-.5-.9-.9c-3.7 2.9-9.8 2.7-13.1 0c-.6.4-1.1.6-.9.9m-27.7 0c3.7 7 11.2 7 14.9 0c.2-.4-.3-.5-.9-.9c-3.7 2.9-9.8 2.7-13.1 0c-.6.4-1.1.6-.9.9");
}

.pyqr-0b4t {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffe8a6, #ffe8a6);
}

.q-ob0owtj {
  cx: 24px;
  cy: 17.2px;
  r: 4px;
}

.r_w28qzwq {
  cx: 39px;
  cy: 9.2px;
  r: 2px;
}

.sek9l58ct {
  cx: 46px;
  cy: 52.6px;
  r: 4px;
}

.vtqnjlbta {
  d: path("M24.2 10.8c0 2.8 2.2 5 5 5s5-2.2 5-5s-2.2-5-5-5c-2.8-.1-5 2.2-5 5");
}

.x2stddcav {
  cx: 52px;
  cy: 50px;
  r: 2px;
}

.yj94e4bca {
  cx: 50px;
  cy: 35.2px;
  r: 7px;
}

</style>

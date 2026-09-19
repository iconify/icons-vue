<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="el83uvksg"/><path class="t341o0bru"/><g class="cm1o77xew"><circle class="yj94e4bca"/><path class="dosoipbww"/><circle class="ls1yo1gbk"/><circle class="r_w28qzwq"/><circle class="x2stddcav"/><circle class="sek9l58ct"/><path class="z70g0ibkl"/></g><g class="y16l70baz"><path class="mbtwwp9jn"/><circle class="hg7lxphel"/><circle class="lvjz7-bia"/><circle class="hqsly9zby"/><circle class="fx05f8yqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:first-quarter-moon" /></template>
<style>
.cm1o77xew {
  fill: var(--svg-color--f4dc9f, #f4dc9f);
}

.dosoipbww {
  d: path("M30.1 43.3c.1 5.1.4 9.5.7 12.8c1.5-1.6 2.3-3.7 2.3-6c.1-2.7-1.1-5.1-3-6.8");
}

.el83uvksg {
  fill: var(--svg-color--ffe8a6, #ffe8a6);
  d: path("M32 2c-1.1 0-2 13.4-2 30s.9 30 2 30c16.6 0 30-13.4 30-30S48.6 2 32 2");
}

.fx05f8yqh {
  cx: 15px;
  cy: 15.7px;
  r: 2px;
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

.mbtwwp9jn {
  d: path("M24.2 41h-.4c.2-.6.4-1.3.4-2c0-3.3-2.7-6-6-6s-6 2.7-6 6c0 2.9 2 5.2 4.7 5.8c-1 1.5-1.6 3.2-1.6 5.2c0 5 4 9 9 9c2.6 0 5-1.1 6.7-3c-.3-3.2-.5-7.6-.7-12.8c-1.7-1.3-3.8-2.2-6.1-2.2M24 21.2c2.2 0 4-1.8 4-4c0-.6-.2-1.2-.4-1.8c.5.2 1 .3 1.6.3c.4 0 .8-.1 1.2-.2c.2-3.9.4-7.1.7-9.5c-.6-.2-1.2-.4-1.8-.4c-2.8 0-5 2.2-5 5c0 1 .3 1.9.8 2.6c-.3-.1-.6-.1-.9-.1c-2.2 0-4 1.8-4 4c-.2 2.4 1.6 4.1 3.8 4.1");
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

.t341o0bru {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M30 32c0-16.6.9-30 2-30C15.4 2 2 15.4 2 32s13.4 30 30 30c-1.1 0-2-13.4-2-30");
}

.x2stddcav {
  cx: 52px;
  cy: 50px;
  r: 2px;
}

.y16l70baz {
  fill: var(--svg-color--464d51, #464d51);
}

.yj94e4bca {
  cx: 50px;
  cy: 35.2px;
  r: 7px;
}

.z70g0ibkl {
  d: path("M34.2 10.8c0-2.1-1.3-3.9-3.2-4.6c-.3 2.4-.5 5.6-.7 9.5c2.2-.6 3.9-2.6 3.9-4.9");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y5_2ecbqw"/><path class="v7t3ihbvq"/><g class="cm1o77xew"><path class="v8e_babzn"/><circle class="hg7lxphel"/><circle class="lvjz7-bia"/><circle class="hqsly9zby"/><circle class="fx05f8yqh"/></g><g class="y16l70baz"><circle class="yj94e4bca"/><path class="zbk9zq8vb"/><circle class="r_w28qzwq"/><circle class="x2stddcav"/><circle class="sek9l58ct"/><path class="m3g-yredx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:last-quarter-moon" /></template>
<style>
.cm1o77xew {
  fill: var(--svg-color--f4dc9f, #f4dc9f);
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

.lvjz7-bia {
  cx: 8.1px;
  cy: 39px;
  r: 2px;
}

.m3g-yredx {
  d: path("M33.2 7.8c.1 1.5.3 3.3.4 5.3c.4-.7.6-1.5.6-2.3c0-1.2-.4-2.2-1-3");
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

.v7t3ihbvq {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M32 2c1.1 0 2 13.4 2 30s-.9 30-2 30c16.6 0 30-13.4 30-30S48.6 2 32 2");
}

.v8e_babzn {
  d: path("M24.2 41h-.4c.2-.6.4-1.3.4-2c0-3.3-2.7-6-6-6s-6 2.7-6 6c0 2.9 2 5.2 4.7 5.8c-1 1.5-1.6 3.2-1.6 5.2c0 5 4 9 9 9s9-4 9-9c-.1-4.9-4.2-9-9.1-9M24 21.2c2.2 0 4-1.8 4-4c0-.6-.2-1.2-.4-1.8c.5.2 1 .3 1.6.3c1.9 0 3.6-1.1 4.4-2.7c-.1-2-.2-3.8-.4-5.3c-.9-1.2-2.4-2.1-4-2.1c-2.8 0-5 2.2-5 5c0 1 .3 1.9.8 2.6c-.3-.1-.6-.1-.9-.1c-2.2 0-4 1.8-4 4s1.7 4.1 3.9 4.1m9.9-.5c0-1.6-.1-3.2-.2-4.7c-.4.6-.7 1.4-.7 2.2c0 1 .3 1.8.9 2.5");
}

.x2stddcav {
  cx: 52px;
  cy: 50px;
  r: 2px;
}

.y16l70baz {
  fill: var(--svg-color--464d51, #464d51);
}

.y5_2ecbqw {
  fill: var(--svg-color--ffe8a6, #ffe8a6);
  d: path("M34 32c0-16.6-.9-30-2-30C15.4 2 2 15.4 2 32s13.4 30 30 30c1.1 0 2-13.4 2-30");
}

.yj94e4bca {
  cx: 50px;
  cy: 35.2px;
  r: 7px;
}

.zbk9zq8vb {
  d: path("M37 14.2c-1.4 0-2.6.7-3.3 1.8c.1 1.5.1 3 .2 4.7c.7.9 1.9 1.6 3.1 1.6c2.2 0 4-1.8 4-4s-1.8-4.1-4-4.1");
}

</style>

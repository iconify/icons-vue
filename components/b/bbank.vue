<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bq6-n7c8t"/><path class="omzwuccbk"/><path class="c_vjpdb1w"/><path class="hmhmkz2xm"/><path clip-rule="evenodd" class="y_9z25bzt"/><path class="x9o5mj4pa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bbank" /></template>
<style>
.bq6-n7c8t {
  fill: var(--svg-color--f26122, #f26122);
  d: path("M4.91 3h1.637v10.907H4.91z");
}

.c_vjpdb1w {
  fill: var(--svg-color--f26122, #f26122);
  d: path("M19.09 13.907a7.09 7.09 0 0 1-6.15 7.03A7.089 7.089 0 0 1 6.548 9.381v4.526a5.453 5.453 0 1 0 1.636-3.894V7.93a7.09 7.09 0 0 1 10.906 5.977");
}

.ft5dv1b6b {
  fill: none;
}

.hmhmkz2xm {
  fill: var(--svg-color--f6851f, #f6851f);
  d: path("M19.088 13.907c0-4.614-5.59-6.686-9.358-4.963a5.5 5.5 0 0 0-1.548 1.074V7.935a7.09 7.09 0 0 1 10.906 5.972");
}

.omzwuccbk {
  fill: var(--svg-color--f6851f, #f6851f);
  d: path("M4.91 3h1.637v3.817S6.274 4.363 4.91 3");
}

.x9o5mj4pa {
  fill: var(--svg-color--f26122, #f26122);
  d: path("m8.728 10.362l1.636-.818v2.073a3.256 3.256 0 0 1 4.292.927c-1.048 0-2.525-.055-3.474.49c-1.615.933-1.833 3.338-1.833 3.338a3.26 3.26 0 0 1-.621-1.92z");
}

.y_9z25bzt {
  fill: var(--svg-color--f6851f, #f6851f);
  fill-rule: evenodd;
  d: path("m10.364 9.544l-1.636.818v4.09a3.272 3.272 0 1 0 1.636-2.835zm0 4.908a1.637 1.637 0 1 0 3.273 0a1.637 1.637 0 0 0-3.273 0");
}

</style>

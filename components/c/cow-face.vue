<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hy3uambhp"/><path class="h0bg-0nlk"/><path class="ph042wbkt"/><path class="c2dj_0bnf"/><ellipse class="um4l6b9bd"/><ellipse class="ys785bzgc"/><path class="kok_kwbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cow-face" /></template>
<style>
.c2dj_0bnf {
  fill: var(--svg-color--e6aaaa, #e6aaaa);
  d: path("M35 28c0 5.522-4.478 8-10 8H11c-5.523 0-10-2.478-10-8s4.477-10 10-10h14c5.522 0 10 4.478 10 10");
}

.h0bg-0nlk {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M1 1c-1.01.99 1 8 5 9s4-5 3-5C5 5 3.042-1 1 1m34.297 0c1.011.99-1 8-5 9s-4-5-3-5c4 0 5.959-6 8-4");
}

.hy3uambhp {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M4 8s-4 2-4 11c0 0 6-1 7-3c0 0 2-12.25-3-8m27.995.043s4 2 4 11c0 0-6-.999-7-2.999c0 0-2-12.251 3-8.001");
}

.kok_kwbmk {
  fill: var(--svg-color--272b2b, #272b2b);
  d: path("M11 12s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2zm10 0s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2z");
}

.ph042wbkt {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M21.976 31h-7.951C8.488 31 4 26.512 4 20.976v-8.951C4 6.488 8.488 2 14.025 2h7.951C27.512 2 32 6.488 32 12.025v8.951C32 26.512 27.512 31 21.976 31");
}

.um4l6b9bd {
  cx: 9.5px;
  cy: 26px;
  fill: var(--svg-color--c1694f, #c1694f);
  rx: 1.5px;
  ry: 3px;
}

.ys785bzgc {
  cx: 26.5px;
  cy: 26px;
  fill: var(--svg-color--c1694f, #c1694f);
  rx: 1.5px;
  ry: 3px;
}

</style>

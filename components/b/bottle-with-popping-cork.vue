<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="odniw0m6n"/><path class="ac2glybgn"/><path class="plic5pb1r"/><path class="my5kexbti"/><path class="n1pbcvvun"/><path class="ots2tpmjx"/><g class="id5hnh2ix"><path class="rebe2kbag"/><ellipse transform="rotate(-21.956 9.231 27.669)" class="cvi0ljbdy"/><ellipse transform="rotate(-48.523 26.177 11.602)" class="n7j_hzb7k"/><ellipse transform="rotate(-35.217 12.332 28.66)" class="e6g9whbxg"/><ellipse transform="rotate(-20.022 19.065 4.78)" class="ru73kqz4e"/><ellipse transform="rotate(-10.857 23.95 6.34)" class="jb6ca4bcn"/></g><path class="f7r_2ac_i"/><path class="q0q3ysb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:bottle-with-popping-cork" /></template>
<style>
.ac2glybgn {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M18.3 26.8s1.7-2.2 5.6-3.2c3.1-.9 2.3-3.7 3.8-5.2l1.3 4.2l-1 4.2l.6 1.5s-1.7-1.2-2.4-1.3c-2.6-.3-7.5.2-7.9-.2");
}

.cvi0ljbdy {
  cx: 9.2px;
  cy: 27.7px;
  rx: 1.3px;
  ry: 0.9px;
}

.e6g9whbxg {
  cx: 12.3px;
  cy: 28.7px;
  rx: 1px;
  ry: 0.7px;
}

.f7r_2ac_i {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("m8.9 10.1l-2.3 3.5c-.7 1.1-.4 2.6.7 3.4l1 .7c.8.6 1.9.5 2.7 0l2.2 1.5c1.1.7 2.6.4 3.4-.7l.7-1c.7-1.1.4-2.6-.7-3.4l-2.2-1.5c.2-.9-.2-2-1-2.5l-1-.7c-1.3-.7-2.8-.4-3.5.7");
}

.id5hnh2ix {
  fill: var(--svg-color--ede2d1, #ede2d1);
}

.jb6ca4bcn {
  cx: 24px;
  cy: 6.3px;
  rx: 0.5px;
  ry: 0.8px;
}

.my5kexbti {
  fill: var(--svg-color--ffe791, #ffe791);
  d: path("M39.9 31.3c-.5-.2-1.1-.4-1.7-.7c-6.1-2.6-9.2-6.8-9.2-6.8l-1 2.7l.7 1.9l-1.4-1l-3.6.8s4.5 3.4 7.3 9.9c.2.6.4 1.1.7 1.6l1.7-1.7l.7 1.7l2.7-1.8l1.1-.3l.3-1.1l1.8-2.7l-1.7-.7z");
}

.n1pbcvvun {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M28.7 28.4s-2.4-2.1-5.1-.2l1.7 1.5c.9-.6 2.3-1 3.9-.7c0 0-.6-2.1.9-3.9l-.9-1c-.6.7-1.8 2.9-.5 4.3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n7j_hzb7k {
  cx: 26.2px;
  cy: 11.6px;
  rx: 0.8px;
  ry: 0.5px;
}

.odniw0m6n {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  d: path("M18.3 26.8s1.7-2.2 5.6-3.2c3.1-.9 2.3-3.7 3.8-5.2l1.3 4.2l-1 4.2l.6 1.5s-1.7-1.2-2.4-1.3c-2.6-.3-7.5.2-7.9-.2");
}

.ots2tpmjx {
  fill: var(--svg-color--ffe791, #ffe791);
  d: path("M25.9 26.3c-.8-.4-2.4-.3-3.9.4c0 0 0-.8-.6-.8c-.5-.1-2.1.8-3.2.9c0 0 .7.9.6 1.7s1.6-.9 2.4-1.1c0 0-.3 1.1-.4 2.2c-.1 1 6-3 7.8-1.2c.1 0-1.5-1.6-2.7-2.1m2.8 2.1s-1.4-1.4-1.1-3.9c0 0 1.2-.4.8-.8s-1.6.4-1.4-1.4s1-2.6.7-3.9c0 0 1.7-.3 1.9 1c.1 1.3-.5 2.5.2 2.4c1-.1 2.1.5.5 2.1c-1.7 1.6-2.2 3.2-1.6 4.5m31 17.1l-14 14c-2.5-1.6-4.6-3.7-6.2-6.2l14-14C56 41 58 43 59.7 45.5");
}

.plic5pb1r {
  fill: var(--svg-color--46732f, #46732f);
  d: path("M38.3 30.7c-6.2-2.6-6.7-2.9-8.6-4.8l-1.2-2.6c-.3-.3-.3-1.1-.9-1.7s-2.8-1.3-3.4-2c0 0 .2-.4-.1-.7s-1.3.3-2.9 2c-1.6 1.6-2.3 2.6-2 2.9s.7.1.7.1c.6.6 1.4 2.8 2 3.4s1.4.6 1.7.9l2.6 1.2c1.9 1.9 2.1 2.4 4.7 8.7c2.2 5.3 3.6 11.1 6.9 16c1.9 2.9 5.3 6.5 9.2 7.7c.6.2 1.8.5 2.6-.3l11.8-11.9c.8-.8.5-2.1.3-2.7c-1.1-3.8-4.8-7.3-7.6-9.3c-4.7-3.3-10.6-4.7-15.8-6.9");
}

.q0q3ysb_i {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M8.9 10.1s1.3-.8 2.6.1c.4.2.7.5 1 .7c.2.2.8 1-.3 2.7c-1.3 2-1.5 3.3-1.5 3.3s1.9-3.8 4-2.7c1.5.8 3.4 1.9 1.9 4.2l.7-1c.7-1.1.4-2.6-.7-3.4l-2.2-1.5c.2-.9-.2-2-1-2.5l-1-.7c-1.3-.6-2.8-.3-3.5.8");
}

.rebe2kbag {
  d: path("M18.5 22.7c.2-1.2-7.9-.7-10.4-.3c-5.1.7-4.5 6.7.2 3.5c4.3-2.9 10.2-2.9 10.2-3.2m5.7-10.2c.2.3 4.3-8 2.9-7.5c-1.1.6-3 7.2-2.9 7.5m-3 7.9c.3-1.1-5.5-17.4-7.1-18.2s-3.9.7 2.6 10.9c2.8 4.4 3.9 9.3 4.5 7.3m-4.3 3.9c-1.9.4-5.1 3.7-3.4 3c1.7-.6 4.6-3.3 3.4-3m6.2-6c1.3-1.2 4.4-4.6 2.8-4.1c-1.4.3-4.1 5.3-2.8 4.1m-1.3-10c-1 1.2-.7 7.7.1 9.8c.8 2.2.8-11.1-.1-9.8m-10.2 12c3.9-1.9-11.5-2.2-9.4-.4s7.6 1.2 9.4.4");
}

.ru73kqz4e {
  cx: 19.1px;
  cy: 4.8px;
  rx: 1.1px;
  ry: 1.6px;
}

</style>

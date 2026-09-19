<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="jeunsn1yj"><path class="s2qyuko7o"/><path class="fpptixbcv"/></g><path class="wcnd36bws"/><g class="uodwj4bii"><path class="khd5ccbpe"/><path class="m66g5vzqk"/></g><path class="kjikyhbiy"/><path class="xvotyu4eq"/><path class="jkmvu4bpw"/><path class="v5zm3jbpj"/><path class="c5nni5oex"/><path class="an8p38g1q"/><path class="gb4afupda"/><path class="dqq8yzqnb"/><path class="rn5ukbb7l"/><path class="sy2r7mlnl"/><path class="nheoky3ki"/><path class="ts4f09b5x"/><path class="u0fh4p2_x"/><g class="uodwj4bii"><path class="u0i0bz4-b"/><path class="ff92q5jbf"/></g><path class="unav4bmrn"/><path class="u4kfc8b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:cat" /></template>
<style>
.an8p38g1q {
  fill: var(--svg-color--4c5359, #4c5359);
  d: path("M39.3 9.4C18.5 9.4 16.5 24 16.5 32.1c0 3.4 10.2 13.9 22.7 13.9C51.8 46 62 35.5 62 32.1C62 24 60 9.4 39.3 9.4");
}

.c5nni5oex {
  fill: var(--svg-color--f7a4a4, #f7a4a4);
  d: path("M22.5 8.8c-.9.5-1.8 8.7-.4 11.1L32 14c-1.3-2.3-8.7-5.7-9.5-5.2");
}

.dqq8yzqnb {
  fill: var(--svg-color--93e67f, #93e67f);
  d: path("M33 26.7S30.9 29 28 29c-3.1 0-5-4.4-5-4.4s2.1-2.4 5.8-1.4c3.5.8 4.2 3.5 4.2 3.5");
}

.ff92q5jbf {
  d: path("M42.4 33.1c-.6-.7-2.5-.8-3.1-.8s-2.5.1-3.1.8c-.4.5-.1 1.8 1.1 3c.7.7 1.4.9 2 .9s1.3-.2 2-.9c1.2-1.2 1.5-2.5 1.1-3");
}

.fpptixbcv {
  d: path("M31.8 55.9c-1.8 2.3-9.7 0-11-2.6c-5.2-10.6 0-15.2 0-15.2l11 1.5c0 .1 2.3 13.5 0 16.3");
}

.gb4afupda {
  fill: var(--svg-color--bfffab, #bfffab);
  d: path("M33.5 28.5s-2.4 3.6-6.8 2.5s-4.6-5.4-4.6-5.4s2.4-3.6 6.8-2.5c4.4 1.2 4.6 5.4 4.6 5.4");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.jkmvu4bpw {
  fill: var(--svg-color--f7a4a4, #f7a4a4);
  d: path("M56.2 8.8c-.9-.5-8.2 2.8-9.6 5.2l10 5.9c1.3-2.3.4-10.6-.4-11.1");
}

.khd5ccbpe {
  d: path("M39.2 60.4c2 2.2 8.9 2.1 11.1 0c3-3 2.9-16.7 3-23.3l-13-1.1c.1 0-3.6 21.5-1.1 24.4");
}

.kjikyhbiy {
  fill: var(--svg-color--fff, #fff);
  d: path("m34 43.7l5.3 11.2l5.3-11.2z");
}

.m66g5vzqk {
  d: path("M39.3 60.4c-2 2.2-8.9 2.1-11.1 0c-3-3-2.9-16.7-3-23.3l13-1.1s3.6 21.5 1.1 24.4");
}

.nheoky3ki {
  fill: var(--svg-color--93e67f, #93e67f);
  d: path("M45.5 26.7s2.1 2.3 5 2.3c3.1 0 5-4.4 5-4.4s-2.1-2.4-5.8-1.4c-3.5.8-4.2 3.5-4.2 3.5");
}

.rn5ukbb7l {
  fill: var(--svg-color--4c5359, #4c5359);
  d: path("M29.8 26.6c0 4.9-2.4 4.9-2.4 0s2.4-4.9 2.4 0");
}

.s2qyuko7o {
  d: path("M2.3 36.1c-.2-1-.3-2-.2-2.9c0-1.2.3-2.2.9-3.2c.6-1.1 1.6-2 2.7-2.5c1.1-.6 2.5-.8 3.8-.6c1.2.1 2.4.6 3.4 1.3c.9.6 1.7 1.4 2.4 2.3c1.1 1.5 1.9 3.3 2.3 5.4v.3c.2 1.3-.6 2.5-1.9 2.9c-.2.1-.4.1-.6.1q-1.2.15-2.1-.6c-.6-.5-1-1.1-1.1-1.9c-.2-1.4-.5-2.6-1.1-3.5c-.5-.9-1.3-1.6-2.1-1.8c-.3-.1-.7-.1-1 0c-.4.1-.7.4-.9.7c-.3.4-.5.8-.5 1.4q-.15.9 0 1.8c.2 1.2.6 2.6 1.3 4c.3.6.7 1.3 1.1 2s.9 1.3 1.3 1.8c1.1 1.3 2.1 2.3 3.2 3.1c1.3.9 2.6 1.5 3.9 1.7s2.8.2 4.3-.3c1.2-.3 1.9.1 2.1.7c.2.5-.1 1.3-1.3 1.7h-.1c-1.8.6-3.7.8-5.4.5c-1.7-.2-3.5-1-5.2-2c-1.4-.9-2.6-2.1-3.9-3.5c-.5-.6-1-1.2-1.4-1.7L6 43q-.9-1.05-1.5-2.1c-1.2-1.6-1.9-3.2-2.2-4.8m44.4 19.8c1.8 2.3 9.7 0 11-2.6c5.2-10.6 0-15.2 0-15.2l-11 1.5c0 .1-2.2 13.5 0 16.3");
}

.sy2r7mlnl {
  fill: var(--svg-color--bfffab, #bfffab);
  d: path("M45.1 28.5s2.4 3.6 6.8 2.5s4.6-5.4 4.6-5.4s-2.4-3.6-6.8-2.5c-4.4 1.2-4.6 5.4-4.6 5.4");
}

.ts4f09b5x {
  fill: var(--svg-color--4c5359, #4c5359);
  d: path("M48.7 26.6c0 4.9 2.4 4.9 2.4 0c.1-4.9-2.4-4.9-2.4 0");
}

.u0fh4p2_x {
  fill: var(--svg-color--fff, #fff);
  d: path("M45.9 32.5c-2-1.5-4.2-6.5-6.6-6.5s-4.7 5-6.6 6.5c-3.1 2.4-11.5 5.1-11.5 5.1s8.9 7.6 18.1 7.6s18.1-7.6 18.1-7.6s-8.4-2.7-11.5-5.1");
}

.u0i0bz4-b {
  d: path("M45.7 39.3c-.7.4-1.6.6-2.4.6c-.8-.1-1.6-.3-2.2-.8s-1.1-1.2-1.2-1.9l-.6-3.3l-.6 3.3c-.1.8-.6 1.4-1.2 1.9s-1.4.8-2.2.8c-.9 0-1.7-.1-2.4-.6c-.7-.4-1.4-1.1-1.7-2c0 1 .6 1.9 1.3 2.5s1.8 1 2.7 1.1c1 .1 2-.2 2.9-.8c.5-.3.8-.7 1.2-1.2q.45.75 1.2 1.2c.9.6 1.9.9 2.9.8c1 0 2-.4 2.7-1.1c.8-.6 1.3-1.6 1.3-2.5c-.3.9-.9 1.6-1.7 2");
}

.u4kfc8b0j {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m29.6 61.2l1.4-2.4l-.4 2.8zm3.5.8l.5-3.3l.5 3.3zm3.9-.4l-.4-2.6l1.4 2.3zm11 0l-.4-2.8l1.4 2.4zm-3.6.4l.5-3.3l.5 3.3zm-3.9-.7l1.4-2.3l-.4 2.6z");
}

.unav4bmrn {
  fill: var(--svg-color--fff, #fff);
  d: path("M39 59.6c0 1.1-2.3 1.9-5.2 1.9s-5.2-.9-5.2-1.9c0-1.1 2.3.1 5.2.1c2.8 0 5.2-1.1 5.2-.1m10.9 0c0 1.1-2.3 1.9-5.2 1.9s-5.2-.9-5.2-1.9c0-1.1 2.3.1 5.2.1s5.2-1.1 5.2-.1");
}

.uodwj4bii {
  fill: var(--svg-color--4c5359, #4c5359);
}

.v5zm3jbpj {
  fill: var(--svg-color--4c5359, #4c5359);
  d: path("M18.7 2.2c-2.4 1.4-3.1 15.7-.6 20.1L36 11.7C33.6 7.4 21 .8 18.7 2.2");
}

.wcnd36bws {
  fill: var(--svg-color--fff, #fff);
  d: path("M34.5 55.2c-.1 1.1-2.6 1.7-5.6 1.4s-5.3-1.3-5.3-2.4c.1-1.1 2.4.3 5.4.5c3.1.4 5.6-.5 5.5.5m9.5 0c.1 1.1 2.6 1.7 5.6 1.4s5.3-1.3 5.3-2.4c-.1-1.1-2.4.3-5.4.5c-3.1.4-5.6-.5-5.5.5");
}

.xvotyu4eq {
  fill: var(--svg-color--4c5359, #4c5359);
  d: path("M59.9 2.2C57.5.8 45.1 7.3 42.6 11.7l17.9 10.6c2.4-4.3 1.7-18.8-.6-20.1");
}

</style>

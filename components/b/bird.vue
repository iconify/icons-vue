<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="al7hx3ugy"><path class="s3i0kibcr"/><path class="mlvtd550h"/></g><path class="yaf4m8jjl"/><path class="v2qlrabnx"/><path class="wino7vj8g"/><path class="qbu_2v8gc"/><path class="j_k8atbmg"/><circle class="evdjxnbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:bird" /></template>
<style>
.al7hx3ugy {
  fill: var(--svg-color--42ade2, #42ade2);
}

.evdjxnbab {
  cx: 15.1px;
  cy: 24.9px;
  r: 2.5px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.j_k8atbmg {
  fill: var(--svg-color--297b9d, #297b9d);
  d: path("M39.1 29.2c-10-9.8-20.2 6.2-7.9 12.6C43.3 48 51.6 37 51.6 37s-6.1-1.5-12.5-7.8");
}

.mlvtd550h {
  d: path("m23.7 19.8l-10.5 1.4C18 10 31.9 13.9 31.9 13.9s-7.3 1.6-8.2 5.9");
}

.qbu_2v8gc {
  fill: var(--svg-color--fff, #fff);
  d: path("M37.6 51.7c-15.6 0-14-12-27.9-11.2c5.1 15.8 27.9 11.2 27.9 11.2");
}

.s3i0kibcr {
  d: path("M59.8 24.3s1.1-6.2-3.5-3.4c0 0-.4-6.3-4.3-1.9c0 0-2.1-3.9-4.4-.3c-3.1 4.8-5.2 12.4-3.2 25l3.8-2.5c2.7-7.9 12.4-8.8 13.7-13.1c.9-3-2.1-3.8-2.1-3.8m-37.7-6.7l-9.9 3.6C14.4 9.2 28.8 10 28.8 10s-6.8 3.2-6.7 7.6");
}

.v2qlrabnx {
  fill: var(--svg-color--e08828, #e08828);
  d: path("M33.8 53h-2.1v7.9c-.3.1-2.1-.1-2.9-.1c-1.8 0-3.3 1.3-3.3 1.3h8.3zM25 53h-2.1v7.9c-.3.1-2.1-.1-2.9-.1c-1.8 0-3.3 1.3-3.3 1.3H25z");
}

.wino7vj8g {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M54 36.2c3.9 0-4.1 17.5-23.3 17.5c-13 0-23.9-5.2-23.9-21.5c0-10.1 6.4-18.3 19.5-15c13.3 3.5 6.5 19 27.7 19");
}

.yaf4m8jjl {
  fill: var(--svg-color--ffd93b, #ffd93b);
  d: path("m2 29l5.4-1.4v3.6c0-.1-3.3-.6-5.4-2.2m5.4-1.5L2 24.8c3.6-2.8 7.7-1.9 7.7-1.9z");
}

</style>

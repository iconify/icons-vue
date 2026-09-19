<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e6moybkue"/><path class="mxlubwbhm"/><g class="jeunsn1yj"><ellipse class="vdy3edbkj"/><ellipse class="wv83fibww"/></g><path class="rqpuasbla"/><path class="cyayd-b4y"/><path class="rhih5ybex"/><path class="gqyakjbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:locked-with-key" /></template>
<style>
.cyayd-b4y {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("M51.6 23.5C50.9 12.6 42.4 3.9 32 3.9s-18.9 8.7-19.6 19.7V25c2.2 0 4.2-.6 4.2-1.4C16.5 16.4 22.5 8 32 8s15.5 8.4 15.5 15.5c0 .8 2 1.4 4.2 1.4z");
}

.e6moybkue {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M2 28.3v31.4C2 62.1 3.9 64 6.3 64h51.4c2.4 0 4.3-1.9 4.3-4.3V28.3z");
}

.gqyakjbug {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M43.2 27.3v8.2l2.3 2.2v3.8l-2.3 2.2v5l2.3 2.2v3.8l-2.3 2.2v3.4l4.7 3.8l4.7-3.8v-33C58.1 25.4 62 20.2 62 14c0-7.7-6.3-14-14.1-14s-14 6.3-14 14.1c0 6.1 3.9 11.3 9.3 13.2m9.4-17.9c0 2.6-2.1 4.6-4.6 4.6c-2.6 0-4.6-2.1-4.6-4.6c0-2.6 2.1-4.6 4.6-4.6s4.6 2.1 4.6 4.6");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.mxlubwbhm {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M62 24c0-2.4-1.9-4.3-4.3-4.3H6.3C3.9 19.6 2 21.6 2 24v4.3h60z");
}

.rhih5ybex {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m36.6 56.4l-1.9-12.3c1.1-.8 1.9-2.2 1.9-3.7c0-2.5-2-4.6-4.6-4.6s-4.6 2.1-4.6 4.6c0 1.5.7 2.9 1.9 3.7l-1.9 12.3z");
}

.rqpuasbla {
  fill: var(--svg-color--dfe9ef, #dfe9ef);
  d: path("M32 0C19.1 0 8.6 10.6 8.6 23.5c0 .8 1.6 1.4 3.8 1.4v-1.4c.8-11 9.3-19.7 19.6-19.7c10.4 0 18.9 8.7 19.6 19.7v1.4c2.2 0 3.8-.6 3.8-1.4C55.4 10.6 44.9 0 32 0");
}

.vdy3edbkj {
  cx: 12.4px;
  cy: 23.5px;
  rx: 5.9px;
  ry: 2.5px;
}

.wv83fibww {
  cx: 51.6px;
  cy: 23.5px;
  rx: 5.9px;
  ry: 2.5px;
}

</style>

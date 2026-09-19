<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="tlvm4nb7u"/><circle class="gkovulnew"/><path class="z6fmmni2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:der-die-das" /></template>
<style>
.gkovulnew {
  cx: 23px;
  cy: 20.3px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.tlvm4nb7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 39v-8h1.3c2.2 0 4 1.8 4 4s-1.8 4-4 4zm0-11v-8h1.3c2.2 0 4 1.8 4 4s-1.8 4-4 4zm0-11V9h1.3c2.2 0 4 1.8 4 4s-1.8 4-4 4zm10.7-1c-.3.6-1 1-1.7 1c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v.7h-4m6-.7c0-1.1.9-2 2-2m-2 0V17");
}

.z6fmmni2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23 22.7V28m5.7-1c-.3.6-1 1-1.7 1c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v.7h-4M27 37c0 1.1-.9 2-2 2s-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2m0 3.3v-5.3m2.2 4.9c.4.3.8.4 1.6.4h.4c.7 0 1.3-.6 1.3-1.3s-.6-1.3-1.3-1.3h-.9c-.7 0-1.3-.6-1.3-1.3s.6-1.3 1.3-1.3h.4c.9 0 1.3.1 1.6.4");
}

</style>

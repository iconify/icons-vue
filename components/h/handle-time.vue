<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="szuki4gni"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handle-time" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.szuki4gni {
  d: path("M4.75 9.25a6.75 6.75 0 0 1 13.5 0m-13.5 0zA2.25 2.25 0 0 1 7 11.5V13a2.25 2.25 0 0 1-2.25 2.25A2.25 2.25 0 0 1 2.5 13v-1.5a2.25 2.25 0 0 1 2.25-2.25M16 11.946V11.5q0-.111.011-.221t.032-.218t.054-.214t.074-.208q.043-.102.095-.2q.052-.097.113-.189t.132-.177q.07-.086.148-.164t.164-.148q.085-.07.177-.132q.092-.061.189-.113q.098-.052.2-.095q.102-.042.208-.074t.214-.054t.218-.032t.221-.011t.221.011t.218.032q.108.022.214.054t.208.074t.2.095q.097.052.189.113t.177.132t.164.148q.078.078.148.164q.07.085.132.177q.061.092.113.189q.052.098.095.2q.042.102.074.208t.054.214t.032.218t.011.221v.418M4.75 15.25v1.25a3 3 0 0 0 3 3h2.75m5-4.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

</style>

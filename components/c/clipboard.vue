<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jw39qsbow"/><path class="v08f61bmk"/><path class="n64khxzqq"/><circle class="jah5ribqj"/><path class="k4y69qbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:clipboard" /></template>
<style>
.jah5ribqj {
  cx: 18px;
  cy: 3px;
  r: 2px;
  fill: var(--svg-color--292f33, #292f33);
}

.jw39qsbow {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M32 34a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2z");
}

.k4y69qbex {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M20 14a1 1 0 0 1-1 1h-9a1 1 0 0 1 0-2h9a1 1 0 0 1 1 1m7 4a1 1 0 0 1-1 1H10a1 1 0 0 1 0-2h16a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H10a1 1 0 1 1 0-2h16a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H10a1 1 0 1 1 0-2h16a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1h-9a1 1 0 1 1 0-2h9a1 1 0 0 1 1 1");
}

.n64khxzqq {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M25 3h-4a3 3 0 1 0-6 0h-4a2 2 0 0 0-2 2v5h18V5a2 2 0 0 0-2-2");
}

.v08f61bmk {
  fill: var(--svg-color--fff, #fff);
  d: path("M29 32a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h20a1 1 0 0 1 1 1z");
}

</style>

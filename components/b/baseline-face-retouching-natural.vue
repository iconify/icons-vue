<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="t8-_arz4f"/><path class="bya-qacdy"/><circle class="pt3nek-ut"/><path class="m46fpw3lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-face-retouching-natural" /></template>
<style>
.bya-qacdy {
  fill: currentColor;
  d: path("m20.77 8.58l-.92 2.01c.09.46.15.93.15 1.41c0 4.41-3.59 8-8 8s-8-3.59-8-8c0-.05.01-.1 0-.14c2.6-.98 4.69-2.99 5.74-5.55A10 10 0 0 0 17.5 10c.45 0 .89-.04 1.33-.1l-.6-1.32l-.88-1.93l-1.93-.88l-2.79-1.27l2.79-1.27l.71-.32A9.9 9.9 0 0 0 12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10c0-1.47-.33-2.87-.9-4.13z");
}

.m46fpw3lq {
  fill: currentColor;
  d: path("M20.6 5.6L19.5 8l-1.1-2.4L16 4.5l2.4-1.1L19.5 1l1.1 2.4L23 4.5z");
}

.pt3nek-ut {
  cx: 15px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

.t8-_arz4f {
  cx: 9px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

</style>

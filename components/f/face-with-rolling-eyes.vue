<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="q1m2erv2p"/><circle class="i9i44z3-b"/><circle class="s2-a01xcc"/><path class="jkw7_vxjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-rolling-eyes" /></template>
<style>
.i9i44z3-b {
  cx: 24.5px;
  cy: 13.5px;
  r: 5.5px;
  fill: var(--svg-color--f4f7f9, #f4f7f9);
}

.jkw7_vxjd {
  fill: var(--svg-color--65471b, #65471b);
  d: path("M23.109 23.424c-2.763-.667-8.873-.06-11.162 4.405a.373.373 0 0 0 .334.546a.38.38 0 0 0 .241-.087c3.084-2.58 7.436-2.58 10.036-2.58c1.635 0 2.536 0 2.536-.708s-.705-1.268-1.985-1.576M10.5 13a2.5 2.5 0 0 0 2.5-2.5c0-1.252-.923-2.28-2.124-2.462a5.4 5.4 0 0 0-2.178.736A2.5 2.5 0 0 0 8 10.5a2.5 2.5 0 0 0 2.5 2.5m13 0a2.5 2.5 0 0 0 2.5-2.5c0-1.252-.923-2.28-2.124-2.462a5.4 5.4 0 0 0-2.177.736A2.48 2.48 0 0 0 21 10.5a2.5 2.5 0 0 0 2.5 2.5");
}

.q1m2erv2p {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.s2-a01xcc {
  cx: 11.5px;
  cy: 13.5px;
  r: 5.5px;
  fill: var(--svg-color--f4f7f9, #f4f7f9);
}

</style>

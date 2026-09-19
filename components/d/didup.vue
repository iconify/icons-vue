<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9uhmqbxt"/><path class="s98vjc-sb"/><path class="mc21-xj5a"/><circle class="smod5kbtn"/><circle class="phlhv7b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:didup" /></template>
<style>
.mc21-xj5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.724 33.467h-7.825v-5.76a2.63 2.63 0 0 1 2.632-2.632h3.127a2.63 2.63 0 0 1 2.632 2.633V32.9a.566.566 0 0 1-.566.566Z");
}

.phlhv7b-f {
  cx: 29.094px;
  cy: 20.901px;
  r: 2.618px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s98vjc-sb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.899 33.467h-9.51a.68.68 0 0 1-.679-.68V26.52a3.24 3.24 0 0 1 3.24-3.24h3.708a3.24 3.24 0 0 1 3.24 3.24z");
}

.s9uhmqbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.23 17.694L25.619 5.168a2.297 2.297 0 0 0-3.238 0L9.771 17.694a2.56 2.56 0 0 0-.757 1.817v15.61a2.39 2.39 0 0 0 2.39 2.39h15.254v5.13c0 .787.973 1.159 1.498.571l5.096-5.7h3.343a2.39 2.39 0 0 0 2.391-2.392V19.512c0-.683-.272-1.337-.756-1.818");
}

.smod5kbtn {
  cx: 19.804px;
  cy: 18.399px;
  r: 3.266px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

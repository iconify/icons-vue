<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="cyqkz_b0r"/><circle class="ucfhvmv0g"/><path class="qri8fl6ad"/><path class="ql_ah2bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:5-in-1" /></template>
<style>
.cyqkz_b0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.022 20.393l2.478-1.349v9.912m-25-.836c.684.574 1.348.836 3.007.836h.286a2.78 2.78 0 0 0 2.779-2.779h0a2.78 2.78 0 0 0-2.78-2.779H11.5v-4.354h6.072");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ql_ah2bwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.513 20.09l11.956-1.452l1.126 9.272l-11.956 1.452z");
}

.qri8fl6ad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.778 23.154l.507 4.173m4.768-.578l-.316-2.6a1.587 1.587 0 0 0-1.766-1.383h0c-.87.106-1.49.896-1.384 1.766m.316 2.599l-.507-4.174");
}

.ucfhvmv0g {
  cx: 23.565px;
  cy: 21.399px;
  r: 0.8px;
  fill: currentColor;
}

</style>

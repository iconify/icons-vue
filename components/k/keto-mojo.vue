<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t2heq5b3f"/><circle class="w5zm28b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keto-mojo" /></template>
<style>
.t2heq5b3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.619 27.459a3.32 3.32 0 0 1-2.285-.907L10.431 19.1a3.33 3.33 0 1 1 4.557-4.857l.012.012l5.492 5.178L33.927 5.314a3.33 3.33 0 1 1 4.824 4.59h0l-15.72 16.52a3.32 3.32 0 0 1-2.412 1.035m7.874.923a3.33 3.33 0 0 0-2.278-.9h-.727l-2.457 2.582a3.33 3.33 0 0 1-4.697.127l-2.873-2.71h-3.8a3.33 3.33 0 0 0-3.33 3.33v8.648a3.33 3.33 0 0 0 6.66 0V34.14h9.908l9.163 8.592a3.33 3.33 0 0 0 4.555-4.86Z");
}

.w5zm28b6k {
  cx: 20.619px;
  cy: 10.461px;
  r: 4.062px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="rht8u46bd"/><circle class="yohvylw0q"/><path class="l23-isxbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:12percent-club" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.l23-isxbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.35 26.492a2.353 2.353 0 0 0-4.502.961a2.353 2.353 0 0 0 4.502.96m-11.4 1.416l11.55-11.55");
}

.rht8u46bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.5 19.758l2.915-1.587v11.658m2.54-7.796a3.866 3.866 0 0 1 4.628-3.788c1.62.311 2.913 1.712 3.074 3.353c.12 1.22-.266 2.425-1.11 3.165c-1.562 1.371-6.592 5.066-6.592 5.066h7.723");
}

.yohvylw0q {
  cx: 28.38px;
  cy: 20.601px;
  r: 2.43px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

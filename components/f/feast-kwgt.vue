<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jm8-5lslf"/><circle class="f2yjju4lp"/><path class="j7p47fbty"/></g><path class="jp-86fb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:feast-kwgt" /></template>
<style>
.f2yjju4lp {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
}

.j7p47fbty {
  d: path("M36.654 34.492v8.016m3.692 0v-2.053L38.273 38.5l2.073-1.955v-2.053");
}

.jm8-5lslf {
  d: path("M33.43 43.327A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.4 21.4 0 0 1-2.174 9.431");
}

.jp-86fb-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.777 40.445a3.547 3.547 0 0 1-3.184-5.99l4.269-4.269a3.547 3.547 0 0 0-5.016-5.016l-4.27 4.27a3.547 3.547 0 0 1-5.016-5.016l4.27-4.27a3.547 3.547 0 1 0-5.016-5.016l-4.27 4.27a3.547 3.547 0 0 1-5.016-5.016l3.815-3.598a3.44 3.44 0 0 0 .087-4.918");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

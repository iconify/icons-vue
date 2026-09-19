<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jm8-5lslf"/><circle class="f2yjju4lp"/><path class="j7p47fbty"/></g><g class="y9tr6bcfx"><path class="v7xxrdn2e"/><path class="tar_ewlyo"/><path class="cqhl004es"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:floral-kwgt" /></template>
<style>
.cqhl004es {
  d: path("M15.487 27.541a3.987 3.987 0 1 1-3.987 3.987v-3.987z");
}

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

.tar_ewlyo {
  d: path("M17.547 21.494H28.28a6.05 6.05 0 0 1-6.047 6.047H11.5a6.05 6.05 0 0 1 6.047-6.047");
}

.v7xxrdn2e {
  d: path("M20.51 12.485H36.5c0 4.972-4.037 9.01-9.01 9.01H11.5c0-4.973 4.037-9.01 9.01-9.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

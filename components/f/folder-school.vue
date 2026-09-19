<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><g class="y9tr6bcfx"><path class="nhmdwebac"/><path class="t36tb6mry"/><path class="orfm_nx-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-school" /></template>
<style>
.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

.nhmdwebac {
  d: path("m33 24.251l-9-3.518l-9 3.518l9 3.519z");
}

.orfm_nx-b {
  d: path("M25.786 24.251c2.49-.175 4.16-.033 5.067.84s.262 6.276.262 6.276");
}

.t36tb6mry {
  d: path("M18.183 25.496v2.816c0 .905 2.604 1.64 5.817 1.64s5.817-.735 5.817-1.64v-2.816");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

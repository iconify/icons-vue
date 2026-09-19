<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="n1i0-lbeo"/><path class="xn7j1jbzm"/></g><g class="y9tr6bcfx"><path class="b5lckbmaa"/><path class="l3x9_tggj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitget-wallet" /></template>
<style>
.b5lckbmaa {
  d: path("M43.187 37a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

.l3x9_tggj {
  d: path("m40.187 33l-2 8l-2-8l-2 8l-2-8");
}

.n1i0-lbeo {
  d: path("M17.33 4L5.353 15.97c-.72.72-.72 1.88 0 2.6l9.206 9.2h8.94L13.43 17.702a.61.61 0 0 1 0-.866L26.273 4z");
}

.xn7j1jbzm {
  d: path("m37 30.049l1.02-1.02c.72-.72.72-1.879 0-2.599l-9.206-9.2h-8.941l10.07 10.067a.61.61 0 0 1 0 .866L17.102 41h8.943l3.21-3.21");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

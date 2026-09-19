<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><g class="y9tr6bcfx"><circle class="d4vgczbvw"/><path class="vu2_go7cp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-camera" /></template>
<style>
.d4vgczbvw {
  cx: 24px;
  cy: 26.5px;
  r: 7px;
}

.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

.vu2_go7cp {
  d: path("M25.658 23.628h-3.316L20.683 26.5l1.659 2.872h3.316l1.659-2.872zm1.659 2.872l2.747 3.507m-12.123-7.005l2.742 3.498m3.317-7l-1.658 4.128m3.316 5.744L24 33.5m-1.658-4.128l-4.406.626m7.722-6.37l4.406-.626");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6ky2pblw"/><path class="l9ygz6r9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:la-poste" /></template>
<style>
.l9ygz6r9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.213 24.45a48.7 48.7 0 0 1-5.846 6.61H4.5m15.24-9.302c-1.121-1.68-4.483-3.698-8.181-4.818h22.527a2.35 2.35 0 0 1 .77 1.96a6.6 6.6 0 0 1-.93 2.858");
}

.s6ky2pblw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 31.06l39-9.3H19.741s-.897 4.145-15.241 9.3");
}

</style>

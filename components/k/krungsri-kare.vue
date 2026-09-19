<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dg37wzyzr"/><path class="yo16dbdoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-kare" /></template>
<style>
.dg37wzyzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.841 18.722c0-1.674 1.397-3.03 3.119-3.03h0m-3.119-.001v8.03M4.602 11.593v12.12m.002-2.574l5.646-5.46M6.4 19.401l4.44 4.294m9.257-3.004c0 1.674-1.396 3.03-3.119 3.03h0c-1.722 0-3.118-1.356-3.118-3.03v-1.97c0-1.673 1.396-3.03 3.118-3.03h0c1.723 0 3.119 1.357 3.119 3.03m0 5v-8.03m19.475 6.493a3.13 3.13 0 0 1-2.71 1.53h0c-1.722 0-3.118-1.357-3.118-3.03v-1.97c0-1.674 1.396-3.03 3.119-3.03h0c1.722 0 3.118 1.356 3.118 3.03v.984h-6.237");
}

.yo16dbdoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.398 19.698a6.535 6.535 0 0 1-6.535 6.535h0a6.535 6.535 0 0 1-6.535-6.535h0a6.535 6.535 0 0 1 13.07 0m-6.244 8.782c-1.66 4.721-6.5 7.927-11.971 7.927c-5.47 0-10.313-3.205-11.973-7.927");
}

</style>

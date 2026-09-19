<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lkj-yhqhw"/><path class="waaxic-0x"/><circle class="lp_rveb6k"/><path class="k4vmnpogj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:colordict" /></template>
<style>
.k4vmnpogj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.742 22.81v5.855m9.488-7.672v6.572a1.105 1.105 0 0 0 1.105 1.105h.331m-2.596-5.855h2.32m-4.3 4.742a2.21 2.21 0 0 1-1.918 1.113h0a2.21 2.21 0 0 1-2.209-2.21v-1.436a2.21 2.21 0 0 1 2.21-2.209h0a2.21 2.21 0 0 1 1.916 1.11");
}

.lkj-yhqhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2m4.331-2v39h24.87a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

.lp_rveb6k {
  cx: 24.742px;
  cy: 20.104px;
  r: 0.75px;
  fill: currentColor;
}

.waaxic-0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.666 28.665v-8.838h1.988a3.866 3.866 0 0 1 3.867 3.867v1.104a3.866 3.866 0 0 1-3.867 3.867Z");
}

</style>

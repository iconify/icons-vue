<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gurm-3bwe"/><path class="g-cqt-bib"/><path class="s_cmai7ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:efootball" /></template>
<style>
.g-cqt-bib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.903 14.407a21.4 21.4 0 0 1 9.595-9.634c10.596-5.32 23.523-.974 28.84 9.634m-28.795 0h-9.64m28.814 0h9.62M34.65 33.593c-5.295 5.301-13.88 5.301-19.175 0");
}

.gurm-3bwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.543 14.407c5.295-5.301 13.88-5.301 19.174 0");
}

.s_cmai7ol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.29 33.593a21.4 21.4 0 0 1-9.596 9.634c-10.596 5.32-23.523.974-28.839-9.634m28.795 0h9.64m-28.815 0h-9.62m32.55-13.546H4.03m34.375 7.919H4.03m0-7.919c-.434 2.502-.543 5.099 0 7.919m34.375-7.919c.434 2.502.543 5.099 0 7.919");
}

</style>

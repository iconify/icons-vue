<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkv7flq5a"/><path class="vihi2hz1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:healthcoach" /></template>
<style>
.mkv7flq5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.6V12.4a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23.2a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

.vihi2hz1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.004 34.042za2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2a2.006 2.006 0 0 1 2 2v1.3a2.006 2.006 0 0 1-2 2M8.033 13.958v8m0-3.3a2.006 2.006 0 0 1 2-2a2.006 2.006 0 0 1 2 2v3.3m23.934-8v8m0-3.3a2.006 2.006 0 0 1 2-2a2.006 2.006 0 0 1 2 2v3.3m-5.497 4.084v8m0-3.3a2.006 2.006 0 0 1 2-2a2.006 2.006 0 0 1 2 2v3.3m-6.152-19.084v7m-1.1-5.3h2.1m-14.934 4.3a1.94 1.94 0 0 1-1.7 1a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2a2.006 2.006 0 0 1 2 2v.7h-4m13.644-5.4v7a.945.945 0 0 0 1 1h.3M12.366 33.042a1.94 1.94 0 0 1-1.7 1a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2a1.94 1.94 0 0 1 1.7 1m19.466 3.3a1.94 1.94 0 0 1-1.7 1a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2a1.94 1.94 0 0 1 1.7 1m-6.497-9.784a2.006 2.006 0 0 1-2 2a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2a2.006 2.006 0 0 1 2 2m0 3.3v-5.3m.158 15.384a2.006 2.006 0 0 1-2 2a2.006 2.006 0 0 1-2-2v-1.3a2.006 2.006 0 0 1 2-2a2.006 2.006 0 0 1 2 2m0 3.3v-5.3");
}

</style>

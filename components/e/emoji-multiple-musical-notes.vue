<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nllcoixfh"/><path class="lz2r75bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-multiple-musical-notes" /></template>
<style>
.lz2r75bqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 28.506a3.977 3.977 0 1 0 7.953.004v-.004a3.977 3.977 0 1 0-7.953-.004zm11.326 9.72a3.977 3.977 0 1 0 7.952.005v-.005a3.977 3.977 0 1 0-7.952-.002zm13.276-9.72a3.977 3.977 0 1 0 7.953.004v-.004a3.977 3.977 0 1 0-7.953-.004z");
}

.nllcoixfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 5.795h-4.747l.301 22.711m-8.83-12.992h-4.747l.301 22.712m-6.88-32.431h-4.746l.3 22.711");
}

</style>

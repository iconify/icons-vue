<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="crr2954dj"/><path class="woto27b6b"/><path clip-rule="evenodd" class="hfdip6obi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:car" /></template>
<style>
.crr2954dj {
  fill-rule: evenodd;
  d: path("M5.653 2.79a2.5 2.5 0 0 0-1.837 1.823l-1.13 4.523A2.5 2.5 0 0 0 1 11.5v3A2.5 2.5 0 0 0 3.5 17h13a2.5 2.5 0 0 0 2.5-2.5v-3a2.5 2.5 0 0 0-1.685-2.364l-1.131-4.523a2.5 2.5 0 0 0-1.836-1.823A18.4 18.4 0 0 0 10 2.263q-2.175 0-4.348.527M3.5 11a1 1 0 0 0 .97-.758l1.286-5.144a.5.5 0 0 1 .368-.365A16.4 16.4 0 0 1 10 4.263a16.4 16.4 0 0 1 3.876.47a.5.5 0 0 1 .367.365l1.286 5.145a1 1 0 0 0 .97.757a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hfdip6obi {
  fill-rule: evenodd;
  d: path("M12.195 5h-4.39a2 2 0 0 0-1.956 1.58l-.429 2A2 2 0 0 0 7.376 11h5.248a2 2 0 0 0 1.955-2.42l-.429-2A2 2 0 0 0 12.195 5m-4.82 4l.43-2h4.39l.429 2z");
}

.woto27b6b {
  d: path("M16.5 13a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-10 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M4 15.5A1.5 1.5 0 0 1 5.5 17v1a1.5 1.5 0 0 1-3 0v-1A1.5 1.5 0 0 1 4 15.5m12 0a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-3 0v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vsz4n-_3c"/><path class="trr4__war"/><path class="x8rkp3b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-handbag" /></template>
<style>
.trr4__war {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.038 42.5H5.962l1.443-23.418h33.19z");
}

.vsz4n-_3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.391 19.082c.163-8.564 1.27-13.582 8.612-13.582s8.395 5.37 8.45 13.581M42.038 42.5H5.962l1.443-23.418h33.19z");
}

.x8rkp3b1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.866 21.566h6.645v6.645h-6.645zm15.101 0h6.646v6.645h-6.646z");
}

</style>

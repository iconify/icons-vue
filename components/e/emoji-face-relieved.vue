<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="le1rdibsu"/><path class="gznxqol9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-relieved" /></template>
<style>
.gznxqol9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.94 19.365s-1.301 1.044-3.211 1.044c-1.902 0-3.225-1.045-3.225-1.045m-9.008.001s-1.3 1.044-3.21 1.044c-1.903 0-3.225-1.045-3.225-1.045m14.961 10.771s-1.625 1.447-4.013 1.447c-2.378 0-4.03-1.447-4.03-1.447");
}

.le1rdibsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 42.5c10.215 0 18.46-8.285 18.46-18.54c0-10.215-8.245-18.46-18.46-18.46C13.785 5.5 5.5 13.745 5.5 23.96c0 10.255 8.285 18.54 18.54 18.54");
}

</style>

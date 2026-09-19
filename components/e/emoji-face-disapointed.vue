<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="le1rdibsu"/><path class="co-i_guwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-disapointed" /></template>
<style>
.co-i_guwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.924 20.496s-1.58.538-3.374-.116c-1.788-.65-2.673-2.084-2.673-2.084m-9.754 0s-.864 1.426-2.66 2.08c-1.787.65-3.387.12-3.387.12m14.946 11.086s-1.625-1.447-4.013-1.447c-2.378 0-4.03 1.447-4.03 1.447");
}

.le1rdibsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 42.5c10.215 0 18.46-8.285 18.46-18.54c0-10.215-8.245-18.46-18.46-18.46C13.785 5.5 5.5 13.745 5.5 23.96c0 10.255 8.285 18.54 18.54 18.54");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kgf5h7b2e"/><path class="h4ngr0bcg"/><path class="cr-ojverw"/><path class="kc7nftbjr"/><path class="fbve4qblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dmi" /></template>
<style>
.cr-ojverw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.936 16.961s-.108-3.28 3.064-3.28V11.53m0-2.99V5.5m-4.596 4.498h3.02m15.087 29.889H10.488m26.295-5.056s11.566-11.788.788-13.693");
}

.fbve4qblv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.064 16.961s.108-3.28-3.064-3.28V11.53m0-2.99V5.5m4.596 4.498h-3.02M24 19.618v15.213");
}

.h4ngr0bcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.491 34.831S8.166 24.767 11.04 19.028s11.009-2.748 12.959.59");
}

.kc7nftbjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.509 34.831s9.325-10.064 6.451-15.803s-11.009-2.748-12.959.59");
}

.kgf5h7b2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.489 37.274h27.023M10.489 42.5h27.023m-26.295-7.669s-11.566-11.788-.788-13.693");
}

</style>

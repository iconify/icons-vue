<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pjklsbbpj"/><path class="uu6r-85eh"/><path class="afze4wf6x"/><circle class="jr-1h-pbt"/><circle class="at08wmbmh"/><circle class="mv9wcbyhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fiat" /></template>
<style>
.afze4wf6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.545 7.86A17.8 17.8 0 0 1 24 6.223c9.82 0 17.78 7.96 17.78 17.779a17.78 17.78 0 0 1-11.27 16.544");
}

.at08wmbmh {
  cx: 27.515px;
  cy: 41.428px;
  r: 0.75px;
  fill: currentColor;
}

.jr-1h-pbt {
  cx: 41.344px;
  cy: 11.295px;
  r: 0.75px;
  fill: currentColor;
}

.mv9wcbyhz {
  cx: 16.056px;
  cy: 39.906px;
  r: 0.75px;
  fill: currentColor;
}

.pjklsbbpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.354 24.006h2.652m-2.652 8.73V15.938h3.518m2.848 16.798V15.938M28.635 24h-5.127m0 8.736V15.938h3.437s.96 2.89 1.259 4.378c.243 1.212.343 2.451.43 3.685c.092 1.284.084 2.573.1 3.861c.021 1.625 0 4.874 0 4.874m1.128-16.798h5.592m-2.796 16.798V15.938M5.757 35.377a21.5 21.5 0 0 1-.597-21.735m8.016 28.935a21.5 21.5 0 0 1-3.081-2.178");
}

.uu6r-85eh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.185 14.295A21.5 21.5 0 0 1 45.5 24c0 11.874-9.626 21.5-21.5 21.5a21.5 21.5 0 0 1-6.233-.923M7.555 10.15a21.5 21.5 0 0 1 27.117-4.814M6.67 20.036A17.78 17.78 0 0 1 13.042 10m.525 28.396A17.78 17.78 0 0 1 6.224 23.73");
}

</style>

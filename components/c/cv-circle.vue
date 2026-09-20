<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="te62v5gjk"/><path clip-rule="evenodd" class="j5v9d6_4h"/><path clip-rule="evenodd" class="z5ll_zb6h"/><path clip-rule="evenodd" class="zoaogzzkj"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cv-circle" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j5v9d6_4h {
  fill-rule: evenodd;
  d: path("M12.83 11.55c0-1.08-.91-1.86-2.03-1.86s-2.03.78-2.03 1.86v.51c0 .09.04.18.1.24s.15.1.24.1h3.38c.09 0 .18-.04.24-.1s.1-.15.1-.24zM8.75 14.5a.75.75 0 0 1 .75-.75h7a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 1-.75-.75m0 3a.75.75 0 0 1 .75-.75h7a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 1-.75-.75");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.te62v5gjk {
  d: path("M10.8 9.35c.56 0 1.01-.45 1.01-1.01s-.45-1.01-1.01-1.01s-1.01.45-1.01 1.01s.45 1.01 1.01 1.01");
}

.z5ll_zb6h {
  fill-rule: evenodd;
  d: path("M5.5 5.5c0-1.102.898-2 2-2h6.69c.562 0 1.092.238 1.465.631l.006.007l4.312 4.702c.359.383.527.884.527 1.36v10.3c0 1.102-.898 2-2 2h-11c-1.102 0-2-.898-2-2zm8.689 0H7.5v15h11V10.192l-4.296-4.685l-.003-.001z");
}

.zoaogzzkj {
  fill-rule: evenodd;
  d: path("M14.19 3.5a1 1 0 0 1 1 1v4.7h4.31a1 1 0 1 1 0 2h-5.31a1 1 0 0 1-1-1V4.5a1 1 0 0 1 1-1");
}

</style>

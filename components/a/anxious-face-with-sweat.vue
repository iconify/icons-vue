<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="y7z03ccwy"/><path class="a41boif7k"/><g class="fbp0m0b1e"><circle class="jjneibcvg"/><circle class="iduwfmbbg"/></g><path class="s7ddagzwl"/><path class="tqda4nb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:anxious-face-with-sweat" /></template>
<style>
.a41boif7k {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.2 44.8c1.2-2 3.3-3.4 5.8-3.4s4.7 1.3 5.8 3.4z");
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.iduwfmbbg {
  cx: 20.5px;
  cy: 33px;
  r: 4.5px;
}

.jjneibcvg {
  cx: 43.5px;
  cy: 33px;
  r: 4.5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.s7ddagzwl {
  fill: var(--svg-color--917524, #917524);
  d: path("M25.6 17.9c-3.2 2.7-7.5 3.9-11.7 3.1c-.6-.1-1.1 2-.4 2.2c4.8.9 9.8-.5 13.5-3.6c.5-.5-1-2.1-1.4-1.7m24.5 3c-4.2.7-8.5-.4-11.7-3.1c-.4-.4-2 1.2-1.4 1.7c3.7 3.2 8.7 4.5 13.5 3.6c.7-.2.2-2.3-.4-2.2");
}

.tqda4nb4s {
  fill: var(--svg-color--65b1ef, #65b1ef);
  d: path("M62 18.5c0 9.4-12.7 9.4-12.7 0c0-6.9 6.4-13.5 6.4-13.5S62 11.7 62 18.5");
}

.y7z03ccwy {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40.3 48.1c0 4.6-3.7 8.3-8.3 8.3s-8.3-3.7-8.3-8.3s3.7-8.3 8.3-8.3s8.3 3.7 8.3 8.3");
}

</style>

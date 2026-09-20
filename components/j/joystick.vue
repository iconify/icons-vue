<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mqyqabbev"/><path class="dxxvhlbfh"/><path class="nlw1cqa1c"/><path class="ew6hxl32f"/><circle class="am_7-qydo"/><path class="h63-9gbqb"/><path class="wwycp0bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:joystick" /></template>
<style>
.am_7-qydo {
  cx: 18px;
  cy: 7px;
  r: 5px;
  fill: var(--svg-color--da2f47, #da2f47);
}

.dxxvhlbfh {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M10 24.5A1.5 1.5 0 0 1 8.5 26h-3a1.5 1.5 0 0 1 0-3h3a1.5 1.5 0 0 1 1.5 1.5");
}

.ew6hxl32f {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M10 34.5A1.5 1.5 0 0 1 8.5 36h-3a1.5 1.5 0 1 1 0-3h3a1.5 1.5 0 0 1 1.5 1.5m22 0a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1 0-3h3a1.5 1.5 0 0 1 1.5 1.5");
}

.h63-9gbqb {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M25 26a2 2 0 0 1-2 2H13a2 2 0 0 1-2-2v-1c0-1.104 3.896-6 5-6h4c1.104 0 5 4.896 5 6z");
}

.mqyqabbev {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M16 9h4v17h-4z");
}

.nlw1cqa1c {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M34 33a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2h28a2 2 0 0 1 2 2z");
}

.wwycp0bio {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M33 28a1 1 0 0 1-1 1H4a1 1 0 1 1 0-2h28a1 1 0 0 1 1 1");
}

</style>

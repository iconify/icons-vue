<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mmp9q3jtz"/><circle class="lyc92fbxl"/><path class="aikh-rrpp"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hindu-vocab" /></template>
<style>
.aikh-rrpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.486 17.047v4.651m5.834 0v-2.896a1.755 1.755 0 1 0-3.509 0m0 2.896v-4.651m9.355 1.777a1.755 1.755 0 1 0-3.51 0v1.14a1.755 1.755 0 1 0 3.51 0m.001 1.756V14.7m-9.97 11.521l-2.325 7.02l-2.326-7.02m7.284 7.019c-.97 0-1.755-.785-1.755-1.754v-1.14a1.755 1.755 0 1 1 3.51 0v1.14c0 .97-.786 1.755-1.755 1.755m6.913-.884a1.754 1.754 0 0 1-3.279-.87v-1.141a1.755 1.755 0 0 1 3.277-.874m5.391 2.014c0 .97-.786 1.755-1.755 1.755h0a1.755 1.755 0 0 1-1.755-1.755v-1.14c0-.97.786-1.755 1.755-1.755h0c.97 0 1.755.785 1.755 1.754m0 2.896V28.59m1.86 1.755a1.755 1.755 0 1 1 3.51 0v1.141a1.755 1.755 0 1 1-3.51 0m0 1.755v-7.02");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.lyc92fbxl {
  cx: 16.486px;
  cy: 14.898px;
  r: 0.75px;
  fill: currentColor;
}

.mmp9q3jtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.502 14.7v7.02m4.65-7.02v7.02m-4.65-3.523h4.65m16.346-1.127v2.895a1.755 1.755 0 1 0 3.51 0v-2.896m0 2.896v1.755");
}

</style>

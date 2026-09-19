<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="qz6hyibtz"/><path class="wq6lcy27l"/><path class="mubnx4-ve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-feather" /></template>
<style>
.mubnx4-ve {
  d: path("M28.598 29.095c-.493-6.342 1.865-9.413 1.865-9.413c7.788 8.51 6.73 17.165 6.091 19.444M25.5 33.448a26.6 26.6 0 0 1-11.76-6.313c-7.116-6.54-7.111-16.08-7.256-19.902A1.678 1.678 0 0 1 8.48 5.531c14.975 2.954 20.05 18.365 20.05 18.365");
}

.qz6hyibtz {
  d: path("M41.517 42.5S23.69 32.087 13.233 12.984");
}

.wq6lcy27l {
  d: path("M36.554 39.126c-19.217 4.612-20.693-10.228-20.693-10.228");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

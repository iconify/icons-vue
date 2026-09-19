<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><g class="y9tr6bcfx"><path class="sbe7zac9l"/><path class="bz94z6t4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-sync" /></template>
<style>
.bz94z6t4b {
  d: path("m27.937 22.562l-1.75 1.75V19.5H31l-1.75 1.75zm-7.874 7.876l1.75-1.75V33.5H17l1.75-1.75z");
}

.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

.sbe7zac9l {
  d: path("M25.251 32.965a6.585 6.585 0 0 0 3.405-11.122m-5.913-1.808a6.585 6.585 0 0 0-3.398 11.12");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

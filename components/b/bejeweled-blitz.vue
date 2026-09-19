<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r-5e03r1b"/><path class="s4036fbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bejeweled-blitz" /></template>
<style>
.r-5e03r1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.177 16.37L35.807 9H12.192l-7.37 7.37a1.1 1.1 0 0 0-.057 1.496L23.164 39.32a1.1 1.1 0 0 0 1.672 0l18.398-21.454a1.1 1.1 0 0 0-.057-1.496M5 17.15h38.5");
}

.s4036fbre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.8 39L14 17l4-7.8M24.2 39L34 17l-4-7.8M8.5 26.5v15m4-9v13m4-10v6m4-2v7m19-20v16m-4-10v8m-4-5v10m-4-6v3.6m-23-21.6v8m39-9v5");
}

</style>

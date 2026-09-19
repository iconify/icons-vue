<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r-5e03r1b"/><path class="o3t3fkb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bejeweled-3" /></template>
<style>
.o3t3fkb8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.8 39L14 17l4-7.8M24.2 39L34 17l-4-7.8");
}

.r-5e03r1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.177 16.37L35.807 9H12.192l-7.37 7.37a1.1 1.1 0 0 0-.057 1.496L23.164 39.32a1.1 1.1 0 0 0 1.672 0l18.398-21.454a1.1 1.1 0 0 0-.057-1.496M5 17.15h38.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="snclwdouz"/><path class="h6h_hzbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fiitjee-recorded-lectures" /></template>
<style>
.h6h_hzbtk {
  d: path("m32.5 24l-15 8.6V15.4zM8.7 36.5v2.1c0 .5.4.8.8.8h2.9");
}

.snclwdouz {
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4m.5 10.3v-3c0-2.2-1.8-4-4-4h-5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

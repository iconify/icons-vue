<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><g class="y9tr6bcfx"><path class="uenigbbuy"/><path class="rhjw5dbix"/><path class="mxyjgzb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:file-justfile" /></template>
<style>
.mxyjgzb7w {
  d: path("m25.846 22.59l6.911 6.91l-6.911 6.91");
}

.r4h1y5b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

.rhjw5dbix {
  d: path("m20.545 22.59l6.91 6.91l-6.91 6.91");
}

.uenigbbuy {
  d: path("m15.243 22.59l6.911 6.91l-6.911 6.91");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

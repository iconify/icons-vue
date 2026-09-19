<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="boqagzbgn"/><g class="y9tr6bcfx"><circle class="wivn1zb6a"/><path class="wk_rzqbsy"/></g><path class="ijfzzxboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitz" /></template>
<style>
.boqagzbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.22 22.044h7.28l-7.28 9.645h7.28M27.408 19.041v12.648m-1.911-9.645h3.822");
}

.ijfzzxboc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.506 24.41a3.64 3.64 0 0 1 0 7.28H9.5V17.13h6.006a3.64 3.64 0 0 1 0 7.28m0 0H9.5");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.wivn1zb6a {
  cx: 22.321px;
  cy: 17.585px;
  r: 1.274px;
}

.wk_rzqbsy {
  d: path("M22.321 22.044v9.645");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

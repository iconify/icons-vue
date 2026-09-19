<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="kdzaxqbgc"/><path class="dytlwbcfn"/><path class="ulv156wgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blitzmail" /></template>
<style>
.dytlwbcfn {
  d: path("M7.455 19.166V42.5h33.09V19.29c-3.401-4.743-6.817-9.484-12.08-13.79h-8.32c-4.937 3.53-8.948 8.404-12.69 13.665zm2.932 20.299l10.01-8.373");
}

.kdzaxqbgc {
  d: path("M23.563 11.738h8.747l-6.223 10.746l3.41.032l-12.155 18.546l4.484-14.327l-3.591.012z");
}

.ulv156wgq {
  d: path("M23.97 31.243h5.314l8.247 8.104m.148-17.443l-7.63 10.16m-11.143.147L10.11 21.838");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

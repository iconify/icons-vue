<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="vfj5c_b-e"/><path class="poduisvrb"/><path class="zy2q_lbsx"/><path class="ofxcuzbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kwai-lite" /></template>
<style>
.ofxcuzbqq {
  d: path("m34.252 37.958l-.707 2.513c-.206.733.164 1.037.553.632l4.417-4.607c.214-.223.205-.614-.243-.614h-.876c-.318 0-.358-.294-.219-.577l.939-1.913a.464.464 0 0 0-.438-.673H35.11c-.204 0-.39.194-.493.377l-1.947 3.48c-.212.378-.093.703.302.703h1.145c.259 0 .233.327.134.68");
}

.poduisvrb {
  d: path("M36.828 12.706a6.815 6.815 0 1 1-13.63 0a6.815 6.815 0 0 1 13.63 0m0 17.404v-2.265a5.39 5.39 0 0 0-5.39-5.391H17.96a5.39 5.39 0 0 0-5.392 5.39v7.765A5.39 5.39 0 0 0 17.96 41h11.937");
}

.vfj5c_b-e {
  d: path("M23.198 11.76a7.76 7.76 0 0 1-7.76 7.761h0a7.76 7.76 0 0 1-7.76-7.76h0A7.76 7.76 0 0 1 15.437 4h0a7.76 7.76 0 0 1 7.76 7.76");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zy2q_lbsx {
  d: path("m12.569 29.094l-4.483-2.588c-1.198-.692-2.695.173-2.695 1.556v7.353c0 1.383 1.497 2.248 2.695 1.556l4.483-2.588M42.61 37a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

</style>

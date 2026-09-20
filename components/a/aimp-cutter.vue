<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="te8jekbdm"/><path class="ko_go1b5e"/><path class="mn2ca5bug"/></g><circle class="gi82w8bfa"/><path class="cs0povbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aimp-cutter" /></template>
<style>
.cs0povbph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.162 15.616V13.36m-.039-2.175V8.931m.041-2.176V4.5");
}

.gi82w8bfa {
  cx: 24.14px;
  cy: 26.131px;
  r: 0.75px;
  fill: currentColor;
}

.ko_go1b5e {
  d: path("m23.978 29.668l-2.85 3.404c.738 1.709.644 3.692-.683 5.315l-3.435 4.074c-1.632 1.381-4.614 1.412-6.431-.07c-2.034-1.606-2.397-4.792-.982-6.914s3.866-4.496 3.866-4.496c1.232-.819 2.81-.862 4.217-.565l3.476-4.105m2.906-3.595L35.857 8.767c1.015 1.424 2.276 3.391.783 5.919l-9.66 11.492");
}

.mn2ca5bug {
  d: path("M15.122 33.231c2.01-1.168 4.498.872 3.365 3.211l-3.31 4.012c-2.204 1.23-4.548-1.054-3.492-3.287zm14.284 2.97c-.794-2.185 1.655-4.272 3.757-2.742l3.36 3.97c.82 2.386-1.844 4.288-3.854 2.853z");
}

.te8jekbdm {
  d: path("m12.243 8.689l18.335 21.76c1.67-.707 3.31-.113 4.717 1.45l3.044 3.503c1.506 2.16 1.153 5.433-1.05 7.02c-1.865 1.39-4.423 1.42-6.354-.078l-3.931-4.562c-.925-1.518-.484-3.476-.336-4.914L11.152 14.411a5.08 5.08 0 0 1 1.092-5.723Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

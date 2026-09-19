<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ylacr67qm"/><circle class="h7gxd-vkc"/><path class="vzr2p0ofx"/><path class="z0h4wdbfo"/><path class="zmxczpbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asus-router" /></template>
<style>
.h7gxd-vkc {
  cx: 10.456px;
  cy: 36.124px;
  r: 1.705px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vzr2p0ofx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.559 13.341h2.622v19.506h-2.622zm5.261-.839a3.933 3.933 0 0 1-.67 6.493m-6.611-.001a3.933 3.933 0 0 1-.669-6.493");
}

.ylacr67qm {
  width: 31.465px;
  height: 6.555px;
  x: 6.916px;
  y: 32.847px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.866px;
}

.z0h4wdbfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.75 10.719a6.18 6.18 0 0 1-.646 10.033m-10.492-.076a6.18 6.18 0 0 1-.636-9.867");
}

.zmxczpbqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.874 8.598a8.86 8.86 0 0 1-.689 14.165m-14.519-.103a8.86 8.86 0 0 1-.679-13.941m11.768 27.408h2.7m-7.945 0h2.7m-7.945 0h2.7");
}

</style>

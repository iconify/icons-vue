<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5tyqmsjc"/><circle class="t72rfdo5f"/><path class="tnpa1u4ft"/><path class="d24n29x4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gallery365" /></template>
<style>
.d24n29x4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.592 22.327a18.6 18.6 0 0 1-2.416-2.043C8.07 16.18 6.558 11.037 8.797 8.797c2.24-2.239 7.382-.726 11.487 3.379c.778.778 1.46 1.59 2.044 2.416m11.08 11.081a18.6 18.6 0 0 1 2.416 2.043c4.105 4.105 5.618 9.247 3.379 11.487c-2.24 2.239-7.382.726-11.487-3.379a18.7 18.7 0 0 1-2.044-2.416m.001-18.816a18.6 18.6 0 0 1 2.043-2.416c4.105-4.105 9.247-5.618 11.487-3.379c2.239 2.24.726 7.382-3.379 11.487c-.778.778-1.59 1.46-2.416 2.044m-18.816 3.345a18.6 18.6 0 0 0-2.416 2.043C8.07 31.82 6.558 36.963 8.797 39.203c2.24 2.239 7.382.726 11.487-3.379c.778-.778 1.46-1.59 2.044-2.416");
}

.p5tyqmsjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.531 16.164a18.6 18.6 0 0 1-.264-3.153C18.267 7.206 20.834 2.5 24 2.5s5.733 4.706 5.733 10.51c0 1.102-.092 2.157-.263 3.155M23.999 29.5c-7.333 0-7.333-11.002 0-11q.544 0 1.079.107c-3.29 2.588.766 7.457 3.906 4.69q.214-.178.39-.394q.118.542.126 1.097a5.5 5.5 0 0 1-5.501 5.5");
}

.t72rfdo5f {
  cx: 24px;
  cy: 24px;
  r: 9.556px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tnpa1u4ft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.469 31.836c.172.998.264 2.051.264 3.153c0 5.805-2.567 10.511-5.733 10.511s-5.733-4.706-5.733-10.51c0-1.102.092-2.157.263-3.155m13.306-13.304a18.6 18.6 0 0 1 3.153-.264c5.805 0 10.511 2.567 10.511 5.733s-4.706 5.733-10.51 5.733c-1.102 0-2.157-.092-3.155-.263M16.164 18.531a18.6 18.6 0 0 0-3.153-.264C7.206 18.267 2.5 20.834 2.5 24s4.706 5.733 10.51 5.733c1.102 0 2.157-.092 3.155-.263");
}

</style>

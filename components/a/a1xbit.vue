<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgvdgfb-i"/><circle class="a9jvzed-r"/><path class="ny2rtr64p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a1xbit" /></template>
<style>
.a9jvzed-r {
  cx: 33.343px;
  cy: 19.058px;
  r: 0.851px;
  fill: currentColor;
}

.dgvdgfb-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4zm10.76 2.091l4.618 4.618m0-4.618l-4.618 4.618");
}

.ny2rtr64p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.343 22.035v6.441m3.577-8.446v7.231c0 .671.544 1.215 1.215 1.215h.365m-2.856-6.441h2.552M28.83 24a2.243 2.243 0 1 1 0 4.486h-3.7v-8.972h3.7a2.243 2.243 0 0 1 0 4.486m.001 0H25.13m0-4.486h-1.315m1.315 8.972h-1.315m2.456-8.972v-1.59m1.831 1.59v-1.59m-1.831 12.152v-1.59m1.831 1.59v-1.59M9.5 28.861h4.861M9.5 20.462l2.431-1.323m0 0v9.722");
}

</style>

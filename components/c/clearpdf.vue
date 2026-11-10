<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wxhofqbfh"/><path class="felfgdcqd"/><path class="betm-ab9v"/><path class="w3y4fxo6b"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clearpdf" /></template>
<style>
.betm-ab9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.73 42.13V31.58c0-5.22 4.23-9.46 9.45-9.46h11.34c2.45 0 4.8-1.02 6.46-2.82c1.83-2.14 3.84-5.58 4.37-10.88m-13.583 5.5h2.407");
}

.felfgdcqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.38 8.52v.01c-1.41 17.28-14.68 31.2-31.65 33.6c-.73.11-1.45.19-2.2.25h-.01");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.w3y4fxo6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.767 17.622v-7.405h3.702m-12.194 7.405v-7.405h1.666a3.24 3.24 0 0 1 3.24 3.24v.926a3.24 3.24 0 0 1-3.24 3.24zm-8.492 0v-7.405h2.424c1.371 0 2.482 1.114 2.482 2.487s-1.111 2.488-2.482 2.488h-2.424");
}

.wxhofqbfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 23.54c0 5.03-2 9.85-5.55 13.41a19 19 0 0 1-13.4 5.55");
}

</style>

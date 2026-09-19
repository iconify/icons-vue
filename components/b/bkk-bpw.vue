<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o110i5ccw"/><circle class="dok_63bxa"/><path class="ptnb757rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bkk-bpw" /></template>
<style>
.dok_63bxa {
  cx: 33.657px;
  cy: 28.477px;
  r: 9.843px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o110i5ccw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.883 27.188l-1.026 4.104l-1.026-4.104l-1.026 4.104l-1.026-4.104m3.826-.056v-4.103h1.333a1.385 1.385 0 1 1 0 2.77h-1.334m-24.213-6.798v4.441m2.387 0l-1.832-2.22l1.832-2.221m-1.832 2.22h-.555m4.253-2.22v4.441m2.387 0l-1.832-2.22l1.832-2.221m-1.832 2.22h-.555m-7.156-.101a1.11 1.11 0 1 1 0 2.22H6.656V18.9h1.832a1.11 1.11 0 1 1 0 2.22m0-.001H6.656M12.172 9.68H4.5l7.725 7.599h7.672Zm.053 22.942V24.95h7.672v7.672Zm7.672-7.672l7.946-7.391V9.887l-7.946 7.392Z");
}

.ptnb757rv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.658 34.212c4.916-1.88 10.311-1.74 16.064-.092m-2.43-7.455v6.853m-11.538-6.853v6.886m0-3.714l11.538-.035m-7.698-4.648a1.026 1.026 0 0 1 0 2.051H29.9v-4.103h1.693a1.026 1.026 0 1 1 0 2.052m.001 0h-1.693");
}

</style>

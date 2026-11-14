<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmucj9bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delete-all" /></template>
<style>
.cmucj9bpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5h11m-9.75 0v11q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01h4.5q.22 0 .435-.048t.415-.141t.373-.229q.175-.134.315-.304m.428-.911q.034-.182.034-.367v-3.343m0-1.3V8.5M6 5.5h14.5m-1.75 0v7M11 5.5V3h4.5v2.5m0 10l5 5m0-5l-5 5");
}

</style>

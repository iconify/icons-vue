<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg3mhjbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backup-immutable" /></template>
<style>
.jg3mhjbav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.75a7 2.25 0 1 0 14 0a7 2.25 0 1 0-14 0m0 4a7 2.25 0 0 0 14 0m-14 4q0 .055.008.11q.009.056.026.111t.042.109q.025.055.059.109t.075.108t.091.106q.05.053.108.105t.124.103t.139.101t.155.099t.169.096t.184.093q.095.046.198.09q.102.045.211.087q.109.043.224.084q.116.041.237.08q.122.039.249.076t.26.072t.271.068t.281.064l.29.059q.148.028.299.054q.152.026.307.05t.314.045t.321.039t.326.035t.331.03t.335.024q.169.011.339.019t.341.013q.171.006.343.008q.171.003.343.003q.56 0 1.113-.029q.553-.028 1.085-.085q.532-.056 1.029-.139t.947-.191M16.75 17h2.5A1.75 1.75 0 0 1 21 18.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-1A1.75 1.75 0 0 1 16.75 17m-.5 0v-1a1.75 1.75 0 0 1 3.5 0v1");
}

</style>

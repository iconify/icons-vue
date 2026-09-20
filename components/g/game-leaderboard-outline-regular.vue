<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z5hkg0_kc"/><path class="xioi8tbab"/><path class="klx4022eb"/><path class="bih55pzif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:game-leaderboard-outline-regular" /></template>
<style>
.bih55pzif {
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.klx4022eb {
  d: path("M21 21v-7h-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xioi8tbab {
  d: path("M3 21V11h6");
}

.z5hkg0_kc {
  d: path("M9 21V6h6v15Z");
}

</style>

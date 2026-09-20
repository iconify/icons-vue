<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uk0rveqaj"/><path class="ph-bhccoq"/><path class="rdx5t34om"/><path class="qynh2c4wy"/><path class="xbibi3o1e"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crowd-outline-bold" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.ph-bhccoq {
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qynh2c4wy {
  d: path("M7 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rdx5t34om {
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uk0rveqaj {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xbibi3o1e {
  d: path("M13 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

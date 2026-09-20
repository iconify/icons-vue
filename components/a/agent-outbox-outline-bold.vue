<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rk0ztqbwb"/><path class="ag39tfb0x"/><path class="zy0mbfbon"/><path class="inae6abkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-outbox-outline-bold" /></template>
<style>
.ag39tfb0x {
  d: path("M12 15v6h10v-6");
}

.inae6abkl {
  d: path("M14.5 10.5 17 8l2.5 2.5");
}

.rk0ztqbwb {
  d: path("M7.69 3.37a4 4 0 1 1 -3.38 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zy0mbfbon {
  d: path("M17 8v5");
}

</style>

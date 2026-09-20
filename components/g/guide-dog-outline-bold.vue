<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="avtblzbgk"/><path class="nie_edcrf"/><path class="midjlmbqm"/><path class="krhtkbcno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guide-dog-outline-bold" /></template>
<style>
.avtblzbgk {
  d: path("M6 20v-7h10v7");
}

.krhtkbcno {
  d: path("m6 13 -3 -3");
}

.midjlmbqm {
  d: path("m16 7 -3 -3");
}

.nie_edcrf {
  d: path("M16 13V7h5v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

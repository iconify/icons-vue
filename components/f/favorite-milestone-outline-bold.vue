<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ftqzjnb8u"/><path class="g_dn-kxhf"/><path class="euckimbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:favorite-milestone-outline-bold" /></template>
<style>
.euckimbze {
  d: path("M9 8a1.5 1.5 0 0 1 3 0 1.5 1.5 0 0 1 3 0l-3 3Z");
}

.ftqzjnb8u {
  d: path("M6 3v18");
}

.g_dn-kxhf {
  d: path("M6 4h12v10H6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

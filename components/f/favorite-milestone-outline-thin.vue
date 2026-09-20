<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftqzjnb8u"/><path class="g_dn-kxhf"/><path class="euckimbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:favorite-milestone-outline-thin" /></template>
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

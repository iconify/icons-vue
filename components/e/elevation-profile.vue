<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n2gum0idi"/><path class="u7fpvpb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elevation-profile" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n2gum0idi {
  d: path("M3.25 2.75v18.5h18");
}

.u7fpvpb5q {
  d: path("m7.12 16.82l2.51-6.39q.37-.93.99-.15l1.76 2.19q.62.78 1.04-.13l2.66-5.68q.42-.91.75.03l3.59 10.12q.33.94-.67.94h-12q-1 0-.63-.93");
}

</style>

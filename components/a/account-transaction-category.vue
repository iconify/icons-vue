<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q5gfg9bju"/><path class="gh8orgb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-transaction-category" /></template>
<style>
.gh8orgb_p {
  d: path("M16.5 15h1.129a1.5 1.5 0 0 1 1.06.439l1.5 1.5a1.5 1.5 0 0 1 0 2.122l-1.128 1.128a1.5 1.5 0 0 1-2.122 0l-1.5-1.5a1.5 1.5 0 0 1-.439-1.06V16.5a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q5gfg9bju {
  d: path("M14.078 21.247L12 20l-2.5 1.5L7.25 20L5 21.5v-19h14v9.9M8.5 6.5h7m-7 3.5h7m-7 3.5H12");
}

</style>

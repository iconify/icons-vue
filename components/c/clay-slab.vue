<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k408-_fxt"/><path class="n80yh07df"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clay-slab" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k408-_fxt {
  d: path("m4.781 10.491l2.273-2.5a1.5 1.5 0 0 1 1.11-.491h9.945a1.5 1.5 0 0 1 1.11 2.509l-2.273 2.5a1.5 1.5 0 0 1-1.11.491H5.891a1.5 1.5 0 0 1-1.11-2.509");
}

.n80yh07df {
  d: path("M2.5 13v4h14l5-5.5v-4m-5 5.5v4");
}

</style>

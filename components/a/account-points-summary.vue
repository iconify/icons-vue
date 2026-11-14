<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ky7efsb9z"/><path class="mnftxeb0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-points-summary" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ky7efsb9z {
  d: path("M2 9.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.mnftxeb0q {
  d: path("m10.161 6.84l.313.633a1.5 1.5 0 0 0 1.129.82l.698.102a.737.737 0 0 1 .409 1.257l-.505.493a1.5 1.5 0 0 0-.432 1.328l.119.695a.737.737 0 0 1-1.069.777l-.625-.328a1.5 1.5 0 0 0-1.396 0l-.625.328a.737.737 0 0 1-1.069-.777l.119-.695a1.5 1.5 0 0 0-.432-1.328l-.505-.493a.737.737 0 0 1 .409-1.257l.698-.102a1.5 1.5 0 0 0 1.129-.82l.313-.633a.737.737 0 0 1 1.322 0M15 21.5v-3m2.75 3v-5m2.75 5v-7");
}

</style>

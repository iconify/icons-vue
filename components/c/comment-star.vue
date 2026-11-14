<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9_4tgb1k"/><path class="h_lwg36bi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:comment-star" /></template>
<style>
.h_lwg36bi {
  d: path("m12.661 8.84l.313.633a1.5 1.5 0 0 0 1.129.82l.698.102a.737.737 0 0 1 .409 1.257l-.505.493a1.5 1.5 0 0 0-.432 1.328l.119.695a.737.737 0 0 1-1.069.777l-.625-.328a1.5 1.5 0 0 0-1.396 0l-.625.328a.737.737 0 0 1-1.069-.777l.119-.695a1.5 1.5 0 0 0-.432-1.328l-.505-.493a.737.737 0 0 1 .409-1.257l.698-.102a1.5 1.5 0 0 0 1.129-.82l.313-.633a.737.737 0 0 1 1.322 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9_4tgb1k {
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5");
}

</style>

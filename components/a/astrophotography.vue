<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bqsyuubjy"/><path class="cextbuhnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:astrophotography" /></template>
<style>
.bqsyuubjy {
  d: path("M2.5 9a2 2 0 0 1 2-2h3L9 4.5h6L16.5 7h3a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

.cextbuhnr {
  d: path("m12.514 10.792l.164.411a1.5 1.5 0 0 0 1.297.942l.441.029a.554.554 0 0 1 .318.978l-.34.283a1.5 1.5 0 0 0-.496 1.525l.11.428a.554.554 0 0 1-.832.605l-.375-.236a1.5 1.5 0 0 0-1.602 0l-.375.236a.554.554 0 0 1-.832-.605l.11-.428a1.5 1.5 0 0 0-.496-1.525l-.34-.283a.554.554 0 0 1 .318-.978l.441-.029a1.5 1.5 0 0 0 1.297-.942l.164-.411a.554.554 0 0 1 1.028 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

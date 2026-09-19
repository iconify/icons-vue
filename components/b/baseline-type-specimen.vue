<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5j_qdwkr"/><path class="vdqhtdbey"/><path class="r0hr0xiwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-type-specimen" /></template>
<style>
.f5j_qdwkr {
  fill: currentColor;
  d: path("M4 6H2v14c0 1.1.9 2 2 2h14v-2H4z");
}

.r0hr0xiwf {
  fill: currentColor;
  d: path("m13.96 7.17l-1.31 3.72h2.69l-1.3-3.72z");
}

.vdqhtdbey {
  fill: currentColor;
  d: path("M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-3.37 12.5l-.8-2.3H12.2l-.82 2.3H9.81l3.38-9h1.61l3.38 9z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ljwkjqq6l"/><path class="dutg2mbjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:credly" /></template>
<style>
.dutg2mbjl {
  d: path("M38.43 30.338c-6.155 9.527-11.732 12.974-16.309 13.15c-11.453.443-13.139-12.072-12.402-18.944C11.312 9.674 22.99-.053 32.992 10.239");
}

.ljwkjqq6l {
  d: path("M36.198 4.5c-3.25 5.17-4.797 8.54-6.098 15.048");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

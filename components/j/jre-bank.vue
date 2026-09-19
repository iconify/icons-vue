<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ens-6abqg"/><path class="z8k1e_b-h"/><path class="mml4glu5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jre-bank" /></template>
<style>
.ens-6abqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.34 19.001C8.58 23.784 10.218 29.9 15 32.661c4.783 2.761 10.9 1.123 13.66-3.66c2.762-4.783 1.123-10.899-3.66-13.66S14.102 14.218 11.34 19");
}

.mml4glu5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24c-4.748-1.582-7.862-6.773-12.58-11M43.5 24c-4.748 1.582-7.862 6.773-12.58 11m-21.825-.018c7.08 3.454 15.627.841 19.566-5.981m2.245-15.983C23.826 9.564 15.28 12.177 11.34 19m9.445 5c1.332 0 2.412 1.07 2.412 2.39s-1.08 2.39-2.412 2.39h-3.98v-9.56h3.98c1.332 0 2.412 1.07 2.412 2.39S22.117 24 20.785 24m0 0h-3.98");
}

.z8k1e_b-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.96 34.96a15.5 15.5 0 1 1 0-21.92");
}

</style>

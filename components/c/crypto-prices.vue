<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="c-vmy6gfm"/><g class="to-5kdesz"><path class="mjjmmib0x"/><path class="aimy2dt4w"/><path class="ms6lpnabp"/><path class="ukq6semxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crypto-prices" /></template>
<style>
.aimy2dt4w {
  d: path("M14.272 14.082v4.846h3.199c1.357 0 2.457-1.086 2.457-2.423s-1.1-2.422-2.457-2.423z");
}

.c-vmy6gfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.39 42.5l5.421-11.353l1.378 3.084l3.475-9.628l1.744 2.305l2.515-5.563l1.128 1.43L42.5 9.132");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.mjjmmib0x {
  stroke-linecap: round;
  d: path("M14.272 14.082h-1.717");
}

.ms6lpnabp {
  d: path("M14.272 18.928v5.165h3.41c1.446 0 2.619-1.157 2.618-2.582c0-1.426-1.172-2.582-2.619-2.583z");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.ukq6semxh {
  stroke-linecap: round;
  d: path("M14.272 24.09h-1.717m1.713.032v1.589m2.779-1.589v1.589m-2.779-13.379v1.59m2.779-1.59v1.59");
}

</style>

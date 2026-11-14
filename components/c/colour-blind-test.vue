<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-e9cebtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-blind-test" /></template>
<style>
.f-e9cebtq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.563 5.875q-5.629 0-7.719 3.761q-.046.083-.07.176T1.75 10t.024.188t.07.176q2.09 3.761 7.719 3.761q5.588 0 8.061-3.709q.062-.092.094-.199q.032-.106.032-.217t-.032-.217t-.094-.199q-2.473-3.709-8.061-3.709M6.75 10q0-3 3-3t3 3t-3 3t-3-3m14.432 4.818Q19.864 13.5 18.001 13.5H18q-1.864 0-3.182 1.318q-.165.165-.309.338Q13.5 16.369 13.5 18q0 1.864 1.318 3.182T18 22.5t3.182-1.318T22.5 18t-1.318-3.182M15 18q0-2.598 2.25-2.946v5.892Q15 20.598 15 18m6 0q0 2.598-2.25 2.946v-5.892Q21 15.402 21 18");
}

</style>

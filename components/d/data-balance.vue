<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxe6h-ntz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-balance" /></template>
<style>
.nxe6h-ntz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 5.5q0-3.25 8.25-3.25q3.228 0 5.54.771q2.71.903 2.71 2.479v13q0 1.576-2.71 2.479q-2.312.771-5.54.771q-8.25 0-8.25-3.25zm15 9.5V7.473q-.516.275-1.21.506q-2.312.771-5.54.771q-4.732 0-6.75-1.069V15q0 .495 1.684 1.056q2.081.694 5.066.694t5.066-.694Q18.75 15.495 18.75 15");
}

</style>

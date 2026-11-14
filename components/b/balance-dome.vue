<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfnjgpbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balance-dome" /></template>
<style>
.dfnjgpbqi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.27 14.871q.205-3.221 2.543-5.558Q8.376 6.75 12 6.75t6.187 2.563q2.364 2.364 2.548 5.631q.427.182.783.538q.732.732.732 1.768t-.732 1.768t-1.768.732H4.25q-2.5 0-2.5-2.5q0-1.949 1.52-2.379m13.486-4.846Q14.746 8.25 12 8.25t-4.756 1.775q4.756 2.19 9.512 0m1.072 1.149Q15.422 12.375 12 12.375t-5.828-1.201q-1.201 1.578-1.388 3.576h14.432q-.187-1.998-1.388-3.576");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cocmlcbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:horizon-tilted" /></template>
<style>
.cocmlcbkp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25m4.247 9.102l-6 3.5q-.129.075-.219.194t-.128.263t-.018.292t.095.277q.037.064.086.119t.108.1t.125.077q.067.033.138.051q.072.019.145.024q.074.004.147-.006t.143-.034t.134-.061l5.932-3.461q.08-.035.15-.087l5.918-3.452q.129-.075.219-.194t.128-.263t.018-.292t-.095-.277q-.037-.064-.086-.119t-.108-.1t-.125-.077q-.067-.033-.138-.051q-.072-.019-.145-.024q-.074-.004-.147.006t-.143.034t-.134.061z");
}

</style>

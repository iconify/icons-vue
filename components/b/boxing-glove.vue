<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqlmuobbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boxing-glove" /></template>
<style>
.rqlmuobbc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 8.782V8.5q0-2.936 1.907-4.843T13 1.75q3.123 0 5.187 2.063T20.25 9v5q0 2.649-1.373 3.427q.373.584.373 1.323v1q0 1.036-.732 1.768t-1.768.732h-9q-1.036 0-1.768-.732T5.25 19.75v-1q0-1.581 1-2.162v-.37q-3.5-.315-3.5-3.718t3.5-3.718M17.5 16.25q-.132 0-.256.045q-.238-.045-.494-.045h-9V8.5q0-5.25 5.25-5.25q2.502 0 4.126 1.624T18.75 9v5q0 2.25-1.25 2.25M6.25 10.299q-2 .282-2 2.201t2 2.201z");
}

</style>

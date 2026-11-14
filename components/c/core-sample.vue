<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1fx4pbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:core-sample" /></template>
<style>
.e1fx4pbwx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-6.25 0-6.25 2.75v15q0 2.75 6.25 2.75t6.25-2.75v-15q0-2.75-6.25-2.75m4.75 13h-9.5v-3.787q2.195-1.002 4.391.195q2.554 1.394 5.109.497zm-9.5 1.5h9.5v3.25q0 1.25-4.75 1.25T7.25 19.5zm9.5-9.716v3.503q-2.195 1.002-4.391-.195q-2.554-1.394-5.109-.497V6.534q1.562.716 4.75.716t4.75-.716");
}

</style>

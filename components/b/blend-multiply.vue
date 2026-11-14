<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8wue5bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blend-multiply" /></template>
<style>
.r8wue5bgt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25m-.63 6.745Q5.5 10.24 5.5 12t1.245 3.005T9.75 16.25q1.256 0 2.25-.634q.994.634 2.25.634q1.76 0 3.005-1.245T18.5 12t-1.245-3.005T14.25 7.75q-1.256 0-2.25.634q-.994-.634-2.25-.634q-1.76 0-3.005 1.245");
}

</style>

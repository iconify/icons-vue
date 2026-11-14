<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3xtky16o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contrast-check" /></template>
<style>
.o3xtky16o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25h3q1.76 0 3.005 1.245T13.75 6.5v1.75h2.875q2.123 0 3.624 1.501t1.501 3.624v3.25q0 2.123-1.501 3.624t-3.624 1.501h-3.25q-2.123 0-3.624-1.501T8.25 16.625V13.75H6.5q-1.76 0-3.005-1.245T2.25 9.5v-3q0-1.76 1.245-3.005T6.5 2.25m7.25 14q0 2.5 2.5 2.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732q-2.5 0-2.5 2.5");
}

</style>

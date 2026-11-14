<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt5q-cbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-centered" /></template>
<style>
.gt5q-cbar {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 3.25H6.875q-2.123 0-3.624 1.501T1.75 8.375v7.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-7.25q0-2.123-1.501-3.624T17.125 3.25m-6.375 3h2.5q1.036 0 1.768.732t.732 1.768v6.5q0 1.036-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5v-6.5q0-2.5 2.5-2.5");
}

</style>

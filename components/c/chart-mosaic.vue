<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvt_hentq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-mosaic" /></template>
<style>
.bvt_hentq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 1.75h-5q-1.036 0-1.768.732T1.75 4.25v15.5q0 1.036.732 1.768t1.768.732h5q1.036 0 1.768-.732t.732-1.768V4.25q0-1.036-.732-1.768T9.25 1.75m6 0h4.5q1.036 0 1.768.732t.732 1.768v6q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732t-.732-1.768v-6q0-2.5 2.5-2.5M17 15.875q0-2.125-2.125-2.125t-2.125 2.125v4.25q0 2.125 2.125 2.125T17 20.125zm3.125-2.125q2.125 0 2.125 2.125v4.25q0 2.125-2.125 2.125T18 20.125v-4.25q0-2.125 2.125-2.125");
}

</style>

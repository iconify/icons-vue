<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajc0t_dcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:classroom-layout" /></template>
<style>
.ajc0t_dcz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 2.25h7.5q2.5 0 2.5 2.5t-2.5 2.5h-7.5q-2.5 0-2.5-2.5t2.5-2.5m0 8h-3q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h3q1.036 0 1.768-.732t.732-1.768q0-2.5-2.5-2.5m7.5 0h3q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-3q-1.036 0-1.768-.732t-.732-1.768q0-2.5 2.5-2.5m-7.5 6.5h-3q-1.036 0-1.768.732T2.75 19.25t.732 1.768t1.768.732h3q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732m7.5 0h3q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-3q-1.036 0-1.768-.732t-.732-1.768t.732-1.768t1.768-.732");
}

</style>

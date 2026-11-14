<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk-y6fdxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-waffle" /></template>
<style>
.xk-y6fdxc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 2.75h.5q1.036 0 1.768.732T8.25 5.25v.5q0 1.036-.732 1.768T5.75 8.25h-.5q-1.036 0-1.768-.732T2.75 5.75v-.5q0-1.036.732-1.768T5.25 2.75m7 0h-.5q-2.5 0-2.5 2.5v.5q0 1.036.732 1.768t1.768.732h.5q1.036 0 1.768-.732t.732-1.768v-.5q0-2.5-2.5-2.5m6 0h.5q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-.5q-1.036 0-1.768-.732T15.75 5.75v-.5q0-2.5 2.5-2.5m-12.5 6.5h-.5q-1.036 0-1.768.732T2.75 11.75v.5q0 2.5 2.5 2.5h.5q2.5 0 2.5-2.5v-.5q0-1.036-.732-1.768T5.75 9.25m6 0h.5q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-.5q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5m7 0h-.5q-2.5 0-2.5 2.5v.5q0 2.5 2.5 2.5h.5q2.5 0 2.5-2.5v-.5q0-2.5-2.5-2.5m-13.5 6.5h.5q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-.5q-2.5 0-2.5-2.5v-.5q0-1.036.732-1.768t1.768-.732m7 0h-.5q-2.5 0-2.5 2.5v.5q0 2.5 2.5 2.5h.5q2.5 0 2.5-2.5v-.5q0-2.5-2.5-2.5m6.5 0h-.5q-2.5 0-2.5 2.5v.5q0 2.5 2.5 2.5h.5q2.5 0 2.5-2.5v-.5q0-2.5-2.5-2.5m-1.5 2.5q0-1 1-1h.5q1 0 1 1v.5q0 1-1 1h-.5q-1 0-1-1z");
}

</style>

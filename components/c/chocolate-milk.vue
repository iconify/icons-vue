<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mplm-7bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chocolate-milk" /></template>
<style>
.mplm-7bld {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 2.25h-13q-.027 0-.053.002q-.074.005-.145.025q-.072.019-.138.052t-.124.079t-.107.101t-.085.12t-.06.134t-.032.143t-.004.147L3.05 7.23Q3 7.36 3 7.5q0 .196.096.367l.906 12.686q.005.071.023.139t.048.132q.031.063.073.12t.093.105t.111.086q.06.037.125.063q.066.026.135.039q.07.013.14.013h9.05q-.3-.688-.3-1.5v-3.5q0-3.394 3.071-3.716l.333-4.667Q17 7.696 17 7.5q0-.14-.05-.27l.298-4.177q.002-.026.002-.053q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m3.25 11.5h-2.5q-2.5 0-2.5 2.5v3.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-3.5q0-2.5-2.5-2.5m-3.5 3.5v-1q0-1 1-1h2.5q1 0 1 1v1zm0 2.5v-1h4.5v1q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707");
}

</style>

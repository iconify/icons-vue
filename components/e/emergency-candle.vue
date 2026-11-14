<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3n_eyujj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emergency-candle" /></template>
<style>
.p3n_eyujj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.564 1.756Q15.25 4.825 15.25 6.75q0 2.85-2.5 3.201v1.299h1q1.036 0 1.768.732t.732 1.768v6q0 1.036-.732 1.768t-1.768.732h-3.5q-1.036 0-1.768-.732T7.75 19.75v-6q0-2.5 2.5-2.5h1V9.951Q8.75 9.6 8.75 6.75q0-1.925 2.686-4.994q.098-.112.232-.178q.133-.066.282-.076t.29.038q.142.047.254.146q.038.032.07.07");
}

</style>

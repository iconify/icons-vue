<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7_05pdrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:free-shipping-threshold" /></template>
<style>
.t7_05pdrm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.875 1.75h-6.75q-3.375 0-3.375 3.375v3.25q0 1.398.989 2.386q.838.839 1.971.966q-.21.468-.21 1.023q0 1.036.732 1.768q.732.733 1.768.733t1.768-.733t.732-1.768q0-.542-.2-1h2.575q1.067 0 1.895-.576q.015.061.04.119q.024.058.058.111t.076.099q.042.047.091.086q.05.039.105.069t.114.051t.121.031t.125.01h1.127q-.127.436-.127 1q0 2.5 2.5 2.5q1.036 0 1.768-.732t.732-1.768q0-.541-.2-1h1.2q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8.5q0-.149-.057-.287t-.163-.243l-3.5-3.5q-.105-.106-.243-.163T18 4.25h-2.816q-.404-2.5-3.309-2.5m8.875 8.5h-6.062q.562-.821.562-1.875V5.75h2.439l3.061 3.061zm-10.25 12h9q2.75 0 2.75-2.75t-2.75-2.75h-9q2.75 0 2.75 2.75t-2.75 2.75");
}

</style>

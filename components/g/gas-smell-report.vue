<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evvwfd2bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gas-smell-report" /></template>
<style>
.evvwfd2bp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.75H5q-1.139 0-1.945.805q-.805.806-.805 1.945V15q0 2.622 2.5 2.744V21q0 .138.049.267q.049.128.14.231q.1.112.234.177t.283.074t.29-.04t.252-.148l4.287-3.811H19q2.75 0 2.75-2.75V5.5q0-2.75-2.75-2.75M5.5 12q0-2.628 2.303-2.954q.204-1.313 1.192-2.301Q10.24 5.5 12 5.5t3.005 1.245q.988.988 1.192 2.301Q18.5 9.372 18.5 12q0 3-3 3h-7q-3 0-3-3");
}

</style>

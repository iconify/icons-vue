<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-dahb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:family-home-rounded" /></template>
<style>
.ks-dahb6r {
  fill: currentColor;
  d: path("M12.276 16.645q.134-.043.247-.14q.606-.56 1.148-1.088q.543-.527.954-1.033q.412-.506.66-.983q.25-.478.25-.928q0-.835-.57-1.385t-1.367-.55q-.494 0-.897.205t-.701.515q-.26-.31-.678-.515t-.875-.205q-.8 0-1.372.548q-.571.548-.571 1.38q0 .453.238.937q.239.484.651.986t.952 1.03t1.134 1.077q.112.106.245.15q.134.042.276.042t.276-.043M6.616 20q-.667 0-1.141-.475T5 18.386v-7.53l-1.538 1.199q-.178.135-.366.104t-.323-.208t-.11-.365q.023-.189.195-.324l8.148-6.259q.224-.162.478-.243t.519-.08t.51.08t.462.243l8.173 6.26q.171.134.193.322q.02.189-.114.37q-.135.167-.323.198q-.189.03-.36-.104L19 10.856v7.529q0 .666-.475 1.14t-1.14.475z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot4epibuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:incident-chat" /></template>
<style>
.ot4epibuh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 1.75h-15q-1.139 0-1.945.805q-.805.806-.805 1.945V16q0 2.75 2.75 2.75h.25v2.75q0 .125.041.243q.04.119.117.217q.045.059.101.107t.12.085q.064.036.135.06q.07.023.143.032t.147.004t.145-.025q.071-.019.137-.053q.066-.033.124-.078l4.297-3.342H19.5q2.75 0 2.75-2.75V4.5q0-2.75-2.75-2.75m-5.371 5.779l2.869 4.661q.768 1.249.053 2.53Q16.335 16 14.868 16H9.132q-1.467 0-2.183-1.28t.053-2.53l2.869-4.661Q10.604 6.34 12 6.34t2.129 1.189");
}

</style>

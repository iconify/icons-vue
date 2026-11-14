<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="das_gx3_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lead-conversion-rate" /></template>
<style>
.das_gx3_o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.973 1.75H7.027q-1.639 0-2.293 1.504q-.653 1.503.466 2.702l3.781 4.052q.269.288.269.682v2.574q0 1.189 1.011 1.813q1.011.625 2.074.094l1.034-.516q1.382-.692 1.381-2.237V10.69q0-.394.269-.682L18.8 5.956q1.119-1.199.466-2.702q-.654-1.504-2.293-1.504m-4.382 15.288l.229.291q1.43 1.818 1.43 2.671q0 2.25-2.25 2.25T9.75 20q0-.853 1.43-2.671l.229-.291q.092-.118.222-.191t.278-.091t.292.021t.261.132q.072.057.129.129");
}

</style>

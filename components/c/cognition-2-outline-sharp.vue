<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj49o0b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cognition-2-outline-sharp" /></template>
<style>
.pj49o0b8l {
  fill: currentColor;
  d: path("M7 21v-3.762q-1.425-1.3-2.212-2.922T4 10.986q0-3.327 2.333-5.657T12 3q2.702 0 4.884 1.645t2.83 4.25L20.987 14H18v5h-4v2h-1v-3h4v-5h2.7l-.95-3.875q-.575-2.294-2.47-3.71Q14.388 4 12 4Q9.1 4 7.05 6.03Q5 8.062 5 10.97q0 1.494.613 2.84q.612 1.346 1.737 2.392L8 16.8V21zm2.477-7.02q.893 0 1.51-.609l3.381-3.381q.613-.613.613-1.506t-.61-1.509q-.616-.61-1.509-.61t-1.502.61q-.771-.286-1.537-.13t-1.294.684t-.685 1.294t.131 1.537q-.61.616-.61 1.509t.61 1.502t1.502.61");
}

</style>

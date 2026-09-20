<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x55buub7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-quality-rounded" /></template>
<style>
.x55buub7r {
  fill: currentColor;
  d: path("M17.93 21q-2.528 0-5.184-1.266t-4.944-3.555q-2.27-2.288-3.536-4.935T3 6.07q0-.45.3-.76T4.05 5h2.473q.408 0 .712.257q.303.257.411.659L8.142 8.3q.07.42-.025.733t-.333.513l-2.193 2.046q.615 1.117 1.36 2.076t1.59 1.817q.87.87 1.875 1.62q1.003.749 2.203 1.414l2.139-2.177q.244-.263.549-.347t.674-.033l2.104.43q.407.1.661.411t.254.712v2.435q0 .45-.31.75t-.76.3m-4.612-10.318Q12 9.363 12 7.5t1.318-3.182T16.5 3t3.182 1.318T21 7.5t-1.318 3.182T16.5 12t-3.182-1.318m3.455-.409q.112-.111.112-.273V7.192q0-.161-.112-.273t-.273-.111t-.273.111t-.111.273V10q0 .162.111.273t.273.112t.273-.112m.077-4.73q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>

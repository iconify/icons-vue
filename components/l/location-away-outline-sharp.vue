<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt5rcbbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-away-outline-sharp" /></template>
<style>
.jt5rcbbhj {
  fill: currentColor;
  d: path("M3 20V9.5l7-5.288l3.99 3.011q-.278.094-.52.22t-.474.303L10 5.462L4 10v9h4.116v1zm7.5 0v-1.328q0-.366.205-.675q.205-.308.52-.507q1.092-.655 2.297-.976q1.205-.322 2.478-.322t2.478.322t2.297.977q.316.198.52.506q.205.309.205.675V20zm1.035-1h8.93v-.538q-1.029-.596-2.148-.933T16 17.192t-2.317.337t-2.149.933zm2.696-5.632q-.731-.729-.731-1.77t.729-1.771t1.769-.73t1.771.728t.731 1.769t-.728 1.772q-.729.73-1.77.73t-1.771-.728m2.828-.713q.441-.441.441-1.059t-.441-1.058T16 10.096t-1.059.442q-.441.44-.441 1.058t.441 1.059t1.059.441t1.059-.441M16 19");
}

</style>

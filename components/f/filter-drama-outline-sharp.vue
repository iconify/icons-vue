<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7oex9b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-drama-outline-sharp" /></template>
<style>
.d7oex9b_r {
  fill: currentColor;
  d: path("M6.5 20q-2.3 0-3.9-1.6T1 14.5q0-1.95 1.213-3.437T5.25 9.15q.625-2.25 2.475-3.7T12 4q2.975 0 4.988 2.063T19 11q1.875.2 2.938 1.55T23 15.475q0 1.875-1.312 3.2T18.5 20zm0-2h12q1.05 0 1.775-.725T21 15.5t-.725-1.775T18.5 13H17v-2q0-2.075-1.463-3.538T12 6q-1.575 0-2.8.863T7.4 9.075q1.95.325 3.275 1.838T12 14.5h-2q0-1.45-1.025-2.475T6.5 11t-2.475 1.025T3 14.5t1.025 2.475T6.5 18");
}

</style>

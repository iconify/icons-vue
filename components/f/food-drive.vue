<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7bau6bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:food-drive" /></template>
<style>
.s7bau6bmb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.673 3.506q.827.59.827 1.494v6.25h1.25V7.5q0-2 2.5-2t2.5 2V12q0 .116-.035.227q.148.126.29.268Q22.25 13.74 22.25 15.5v2q0 1.76-1.245 3.005T18 21.75H6q-1.76 0-3.005-1.245T1.75 17.5v-2q0-1.76 1.245-3.005q.142-.142.29-.268q-.035-.111-.035-.227V7.5q0-2 2.5-2q.965 0 1.673.506q.827.59.827 1.494v3.75H9.5V5q0-2 2.5-2q.965 0 1.673.506m5.577 7.92V9.398q-.436.102-1 .102t-1-.102v1.852H18q.661 0 1.25.176m-2-3.926q0 .5 1 .5t1-.5t-1-.5t-1 .5M12 5.5q1 0 1-.5t-1-.5t-1 .5t1 .5m1 5.75V6.842Q12.54 7 12 7q-.564 0-1-.102v4.352zM6.75 7.5q0-.5-1-.5t-1 .5t1 .5t1-.5m-2 1.898v2.028q.589-.176 1.25-.176h.75V9.342q-.46.158-1 .158q-.564 0-1-.102");
}

</style>

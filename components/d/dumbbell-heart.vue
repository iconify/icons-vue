<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzsq4mbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dumbbell-heart" /></template>
<style>
.dzsq4mbyb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.75q2.75 0 2.75 2.75V7h8.5V5.5q0-2.75 2.75-2.75t2.75 2.75V10q0 2.75-2.75 2.75T16.25 10V8.5h-8.5V10q0 2.75-2.75 2.75T2.25 10V5.5q0-1.139.805-1.945Q3.861 2.75 5 2.75m12.447 19.257l-2.75-3q-.049-.054-.087-.115q-1.131-1.849.401-3.381q1.369-1.368 2.989-.612q1.62-.756 2.989.612q1.532 1.532.401 3.381q-.038.061-.087.115l-2.75 3q-.05.054-.11.098q-.059.044-.126.075t-.139.049q-.072.017-.145.02q-.074.004-.147-.008q-.073-.011-.143-.036q-.069-.026-.132-.064t-.118-.088q-.024-.022-.046-.046m2.697-3.956q.457-.807-.216-1.479q-.696-.697-1.536-.182q-.089.054-.189.082q-.099.028-.203.028t-.203-.028q-.1-.028-.189-.082q-.84-.515-1.536.182q-.673.672-.216 1.479L18 20.39z");
}

</style>

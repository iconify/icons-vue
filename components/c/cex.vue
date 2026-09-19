<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vqranq7kz"/><path class="ndrlp-bdn"/><path class="axdkmgbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cex" /></template>
<style>
.axdkmgbqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 27l-.242 6.479l-6.33-.426m-.218-19.092l6.468-.196l.103 6.433M15.444 27.84c-8.804-.76-7.331-8.689-.081-9.552M26.56 29.98c-6.294.242-9.402-.253-7.342-12.624c8.643-5.052 15.041 9.31-.264 7.238m21.669 8.827c-4.062 2.532-8.343 5.202-11.945 2.244m.92-23.131c3.188-3.05 7.55-1.082 10.496 1.116");
}

.ndrlp-bdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.982 14.053C34.26 25.09 32.2 34.238 26.813 37.023c-28.286.587-30.852-25.375-.932-25.95c5.57.195 8.954 10.667 17.101 22.21");
}

.vqranq7kz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.82 17.88q5.52 4.59.18 12.32");
}

</style>

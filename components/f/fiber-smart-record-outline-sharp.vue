<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqvxifb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fiber-smart-record-outline-sharp" /></template>
<style>
.fqvxifb0n {
  fill: currentColor;
  d: path("M9 19q-2.925 0-4.962-2.037T2 12t2.038-4.962T9 5t4.963 2.038T16 12t-2.037 4.963T9 19m7-.1v-2q1.75-.35 2.875-1.725T20 12t-1.125-3.175T16 7.1v-2q2.6.35 4.3 2.312T22 12t-1.7 4.588T16 18.9m-3.462-3.362Q14 14.075 14 12t-1.463-3.537T9 7T5.463 8.463T4 12t1.463 3.538T9 17t3.538-1.463");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="han03nbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:enlarger-easel" /></template>
<style>
.han03nbji {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.375 2.25H5.625q-1.398 0-2.386.989q-.989.988-.989 2.386v7.75q0 1.398.989 2.386q.737.738 1.703.925l-1.144 3.051q-.053.139-.048.288q.005.15.067.285q.062.136.171.238t.249.154q.139.053.288.048q.15-.005.285-.067q.136-.062.238-.171t.154-.249L6.52 16.75h10.96l1.318 3.513q.026.07.065.132q.039.063.089.117t.11.097t.128.074q.067.03.139.047t.146.02q.073.002.146-.01t.142-.038t.132-.065t.117-.089t.097-.11t.074-.128t.047-.139t.02-.146q.002-.073-.01-.146t-.038-.142l-1.135-3.027q2.683-.326 2.683-3.335v-7.75q0-1.398-.989-2.386q-.988-.989-2.386-.989M8 5.75h8q2.25 0 2.25 2.25v3q0 .932-.659 1.591T16 13.25H8q-.932 0-1.591-.659T5.75 11V8q0-2.25 2.25-2.25");
}

</style>

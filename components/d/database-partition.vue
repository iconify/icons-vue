<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrthgm_eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-partition" /></template>
<style>
.lrthgm_eh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-8.75 0-8.75 3.75v13q0 3.75 8.75 3.75t8.75-3.75v-13q0-3.75-8.75-3.75m.75 18.988v-4.995q4.536-.089 6.5-1.281V18.5q0 .723-1.856 1.419q-1.95.731-4.644.819m-1.5-4.995v4.995q-2.694-.088-4.644-.819Q4.75 19.223 4.75 18.5v-4.038q1.964 1.192 6.5 1.281m1.5-1.505V9.243q4.536-.089 6.5-1.281V12q0 .723-1.856 1.419q-1.95.731-4.644.819m-1.5-4.995v4.995q-2.694-.088-4.644-.819Q4.75 12.723 4.75 12V7.962q1.964 1.192 6.5 1.281");
}

</style>

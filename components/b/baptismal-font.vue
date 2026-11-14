<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibkd95a3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baptismal-font" /></template>
<style>
.ibkd95a3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.277 3.888Q5.572 5.31 5.301 7.25H4q-.194 0-.364.094q-.131.073-.223.19q-.093.117-.134.26t-.024.292t.089.278l2.5 4.5q.049.088.119.16t.157.122q.086.051.183.078q.097.026.197.026h2.75v4.5h-1q-2 0-2 2q0 .828.586 1.414t1.414.586h7.5q.828 0 1.414-.586t.586-1.414q0-2-2-2h-1v-4.5h2.75q.1 0 .197-.026q.097-.027.183-.078q.087-.05.157-.122t.119-.16l2.5-4.5q.094-.17.094-.364q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 7.25h-1.301q-.271-1.94-1.976-3.362Q14.757 2.25 12 2.25T7.277 3.888m.96 1.153q-1.152.96-1.412 2.209h10.35q-.26-1.249-1.412-2.209Q14.214 3.75 12 3.75T8.237 5.041m2.513 8.209v4.5h2.5v-4.5z");
}

</style>

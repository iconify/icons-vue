<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqlpuwk_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:health-risk-low" /></template>
<style>
.iqlpuwk_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.066 3.434Q14.382 1.75 12 1.75T7.934 3.434T6.25 7.5v9q0 2.382 1.684 4.066T12 22.25t4.066-1.684T17.75 16.5v-9q0-2.382-1.684-4.066M9.25 6.75Q9.25 4 12 4t2.75 2.75q0 2.164-1.702 2.625Q14.75 9.836 14.75 12t-1.702 2.625q1.702.461 1.702 2.625Q14.75 20 12 20t-2.75-2.75q0-2.164 1.702-2.625Q9.25 14.164 9.25 12t1.702-2.625Q9.25 8.914 9.25 6.75");
}

</style>

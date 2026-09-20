<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm4y6fhhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-sad-24-filled" /></template>
<style>
.qm4y6fhhe {
  fill: currentColor;
  d: path("M12 1.998c5.524 0 10.002 4.478 10.002 10.002c0 5.523-4.478 10-10.002 10S2 17.523 2 12C1.999 6.476 6.476 1.998 12 1.998m0 11.5A5.98 5.98 0 0 0 7.712 15.3a.75.75 0 1 0 1.072 1.05A4.5 4.5 0 0 1 12 14.996c1.225 0 2.37.49 3.211 1.347a.75.75 0 1 0 1.07-1.052a5.98 5.98 0 0 0-4.28-1.795M9 8.75a1.25 1.25 0 1 0 0 2.499A1.25 1.25 0 0 0 9 8.75m6 0a1.25 1.25 0 1 0 0 2.499a1.25 1.25 0 0 0 0-2.499");
}

</style>

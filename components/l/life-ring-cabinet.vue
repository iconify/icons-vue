<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouv33vxoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:life-ring-cabinet" /></template>
<style>
.ouv33vxoc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.25h10q1.76 0 3.005 1.245T21.25 6.5v11q0 1.76-1.245 3.005T17 21.75H7q-1.76 0-3.005-1.245T2.75 17.5v-11q0-1.76 1.245-3.005T7 2.25m.581 5.331Q5.75 9.411 5.75 12t1.831 4.419T12 18.25t4.419-1.831Q18.25 14.589 18.25 12t-1.831-4.419Q14.589 5.75 12 5.75T7.581 7.581");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmqgb2b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-gripper" /></template>
<style>
.kmqgb2b_g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 5q0-3.25 3.25-3.25T15.25 5q0 1.749-.941 2.557l1.568 2.614q1.94-.211 2.472 1.923l1.573 6.307q.604 2.425-1.822 3.03q-2.425.604-3.03-1.822l-1.573-6.307q-.471-1.893.903-2.677l-1.471-2.453q-.426.078-.929.078t-.929-.078L9.6 10.625q1.374.784.903 2.677L8.93 19.609q-.605 2.426-3.03 1.822q-2.426-.605-1.822-3.03l1.573-6.307q.532-2.134 2.472-1.923l1.568-2.614Q8.75 6.749 8.75 5");
}

</style>

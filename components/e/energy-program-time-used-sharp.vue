<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo-0ifbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:energy-program-time-used-sharp" /></template>
<style>
.qo-0ifbfo {
  fill: currentColor;
  d: path("M18 11.5q-.788 0-1.513-.26t-1.35-.75l-1.062.968l-.683-.683l1.043-1.023q-.42-.62-.677-1.313T13.5 7q0-1.868 1.316-3.184T18 2.5h4.5V7q0 1.868-1.316 3.184T18 11.5m-1.594-2.298l2.877-2.877l-.733-.708l-2.89 2.89zM2 21V5h9.5v8.5H18V21zm3.73-3.5h1v-6h-1zm3.77 0h1v-9h-1zm3.77 0h1v-3h-1z");
}

</style>

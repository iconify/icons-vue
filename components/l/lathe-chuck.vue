<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7y3anq1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lathe-chuck" /></template>
<style>
.j7y3anq1k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M12 3.25q-2 0-2 2v2q0 2 2 2t2-2v-2q0-2-2-2M9.851 13.97q.685.78 2.149.78t2.149-.78q-.095.447.033.923q.214.801.932 1.215l1.732 1q1.732.998 2.731-.733h.001q.414-.717.2-1.518q-.214-.8-.932-1.215l-1.732-.999q-.718-.415-1.518-.2q-.587.157-.966.584q.12-.454.12-1.027q0-2.75-2.75-2.75T9.25 12q0 .573.12 1.027q-.379-.427-.966-.584q-.8-.215-1.518.199l-1.732 1.001q-.718.414-.932 1.214q-.214.801.2 1.518h.001q.999 1.731 2.731.733l1.732-1q.718-.414.932-1.215q.128-.476.033-.923");
}

</style>

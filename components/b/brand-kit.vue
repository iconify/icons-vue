<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw18zvbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brand-kit" /></template>
<style>
.aw18zvbkq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.75 12.438q1.5.531 1.5 2.562v4.5q0 2.75-2.75 2.75h-15q-2.75 0-2.75-2.75V13q0-1.139.805-1.945q.321-.32.695-.513V4.5q0-1.139.805-1.945Q4.861 1.75 6 1.75h12q2.75 0 2.75 2.75zm-16-2.188H9q.149 0 .287.057t.243.163l1.781 1.78h7.939V4.5q0-1.25-1.25-1.25H6q-1.25 0-1.25 1.25zM14.25 7q0-2.25-2.25-2.25T9.75 7T12 9.25T14.25 7M5 7q0-2.25 2.25-2.25T9.5 7T7.25 9.25T5 7m10.25-.177v-.001l.079-.157q.44-.878 1.421-.878t1.42.877l.08.159q.418.836-.073 1.631q-.492.796-1.427.796t-1.427-.796q-.491-.795-.073-1.631");
}

</style>

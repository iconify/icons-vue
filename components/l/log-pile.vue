<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggtfwdbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:log-pile" /></template>
<style>
.ggtfwdbzu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.464 4.964Q7 6.429 7 8.5q0 1.235.521 2.255q-1.924.077-3.307 1.459Q2.75 13.679 2.75 15.75t1.464 3.536Q5.679 20.75 7.75 20.75t3.536-1.464q.416-.416.713-.881q.298.465.715.882q1.464 1.465 3.536 1.465t3.536-1.465q1.465-1.466 1.464-3.537q.001-2.071-1.464-3.537q-1.382-1.383-3.306-1.46Q17 9.734 17 8.5q0-2.071-1.464-3.536Q14.071 3.5 12 3.5T8.464 4.964M9.75 8.5q0-2.25 2.25-2.25t2.25 2.25T12 10.75T9.75 8.5M5.5 15.75q0-2.25 2.25-2.25T10 15.75T7.75 18T5.5 15.75m10.75-2.25q2.25 0 2.25 2.25T16.25 18T14 15.75t2.25-2.25");
}

</style>

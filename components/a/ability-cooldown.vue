<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf_vr99_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ability-cooldown" /></template>
<style>
.wf_vr99_l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h12q1.76 0 3.005 1.245T22.25 6v12q0 1.76-1.245 3.005T18 22.25H6q-1.76 0-3.005-1.245T1.75 18V6q0-1.76 1.245-3.005T6 1.75m1.227 15.023Q9.204 18.75 12 18.75t4.773-1.977T18.75 12t-1.977-4.773T12 5.25T7.227 7.227T5.25 12t1.977 4.773m9.975-5.523q-.224-1.697-1.49-2.962q-1.265-1.266-2.962-1.49v4.452zM12 12.75h5.202q-.224 1.697-1.49 2.962Q14.175 17.25 12 17.25t-3.712-1.538Q6.75 14.175 6.75 12t1.538-3.712q1.265-1.266 2.962-1.49V12q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs2pm4b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cpap-machine" /></template>
<style>
.vs2pm4b1v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.498 5.94l-.869-1.411Q18.896 3.34 17.5 3.34t-2.129 1.189l-.869 1.411q-.768 1.249-.053 2.53q.716 1.28 2.183 1.28h.104q-.207 5.411-3.486 5.942V15.5q0-1.76-1.245-3.005T9 11.25H6q-1.76 0-3.005 1.245T1.75 15.5V18q0 1.76 1.245 3.005T6 22.25h3q1.76 0 3.005-1.245T13.25 18v-.788q4.75-.493 4.988-7.462h.13q1.467 0 2.183-1.28t-.053-2.53M4.75 16.75Q4.75 14 7.5 14t2.75 2.75T7.5 19.5t-2.75-2.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcq__-b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:envelope-letter" /></template>
<style>
.tcq__-b_e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 3.75H6q-1.76 0-3.005 1.245q-.142.142-.268.29q.139.044.251.137l6.833 5.655q.681-.827 2.189-.827t2.189.827l6.833-5.655q.112-.093.251-.137q-.126-.148-.268-.29Q19.76 3.75 18 3.75m-3.268 8.825q.018.203.018.425q0 2.75-2.75 2.75T9.25 13q0-.222.018-.425L2.022 6.578l-.031-.027Q1.75 7.225 1.75 8v8q0 1.76 1.245 3.005T6 20.25h12q1.76 0 3.005-1.245T22.25 16V8q0-.775-.241-1.449l-.031.027z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_v536b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fork-spoon-rounded" /></template>
<style>
.f_v536b-t {
  fill: currentColor;
  d: path("M6.951 20.856q-.143-.143-.143-.356v-8.04q-1.35-.344-2.08-1.198Q4 10.408 4 9.173V3.5q0-.213.144-.356T4.501 3t.356.144T5 3.5v5.173h1.808V3.5q0-.213.144-.356Q7.096 3 7.308 3q.213 0 .357.144t.143.356v5.173h1.808V3.5q0-.213.143-.356Q9.903 3 10.116 3t.356.144t.144.356v5.673q0 1.235-.73 2.089q-.728.853-2.078 1.199V20.5q0 .213-.144.356T7.307 21t-.356-.144m9.365 0q-.143-.144-.143-.356v-8.371q-1.35-.47-2.079-1.657t-.729-2.878q0-1.898.972-3.246T16.673 3q1.373 0 2.35 1.351T20 7.6q0 1.71-.738 2.894q-.739 1.185-2.089 1.627V20.5q0 .213-.144.356q-.144.144-.356.144q-.213 0-.357-.144");
}

</style>

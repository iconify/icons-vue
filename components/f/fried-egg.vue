<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_4efhbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fried-egg" /></template>
<style>
.c_4efhbqt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.338 14.358Q6.685 19.75 13 19.75q4.02 0 6.53-3.227q2.493-3.206 1.159-6.318q-1.212-2.829-4.425-4.38q-3.062-1.478-6.348-1.07q-3.991.402-5.707 3.712q-1.644 3.172.129 5.891M8.25 12q0-3.75 3.75-3.75T15.75 12T12 15.75T8.25 12");
}

</style>

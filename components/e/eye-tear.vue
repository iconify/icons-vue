<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbxcqh_re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-tear" /></template>
<style>
.rbxcqh_re {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.854 8.62Q5.6 2.25 12 2.25t10.146 6.37q.051.086.078.183q.026.097.026.197t-.026.197q-.027.097-.078.183Q18.4 15.75 12 15.75T1.854 9.38q-.051-.086-.078-.183Q1.75 9.1 1.75 9t.026-.197t.078-.183M12 5.25Q8.25 5.25 8.25 9T12 12.75T15.75 9T12 5.25m4.624 11.084l1.5 2.25l.019.03q1.093 1.819-.525 3.193t-3.236 0t-.525-3.193l.019-.03l1.5-2.25q.041-.061.093-.114q.052-.052.114-.093q.061-.041.129-.07q.068-.028.141-.042t.146-.015q.074 0 .147.014q.072.015.14.043t.13.069q.125.083.208.208");
}

</style>

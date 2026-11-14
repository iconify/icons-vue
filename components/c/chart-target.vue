<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w65up-bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-target" /></template>
<style>
.w65up-bct {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.166 4.166Q5.75 6.583 5.75 10t2.416 5.834q.316.316.65.59l-.883 1.324l-1.857-2.228q-.091-.11-.217-.178q-.131-.072-.279-.088t-.292.026q-.143.043-.259.136t-.187.225l-3 5.5q-.072.131-.088.279t.026.292t.136.259t.225.187q.065.036.135.058t.144.03t.147.001t.145-.027q.07-.021.136-.056q.065-.034.123-.08q.057-.047.105-.103q.047-.057.082-.122l2.472-4.531l1.794 2.152q.047.057.105.103q.057.047.122.081q.066.034.137.055t.144.028t.147-.001t.144-.03t.136-.057q.064-.036.121-.083q.084-.069.144-.16l1.43-2.145q1.77.979 3.946.979q3.417 0 5.834-2.416T22.25 10t-2.416-5.834Q17.417 1.75 14 1.75T8.166 4.166");
}

</style>

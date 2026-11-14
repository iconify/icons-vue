<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7o-k7b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:citizen-feedback" /></template>
<style>
.i7o-k7b6e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.75H5q-1.346 0-2.298.952T1.75 6v9q0 3.122 3 3.245V21q0 .125.041.243q.04.119.117.217q.045.059.101.107t.12.085q.064.036.135.06q.07.023.143.032t.147.004t.145-.025q.071-.019.137-.053q.066-.033.124-.078l4.297-3.342H19q3.25 0 3.25-3.25V6q0-1.346-.952-2.298T19 2.75m-5.795 4.869l.172.473q.164.451.642.491l.623.052q.89.074 1.144.929t-.451 1.403l-.354.275q-.385.3-.266.774l.143.572q.222.889-.533 1.408t-1.505-.007l-.39-.273q-.43-.3-.86 0l-.39.273q-.75.526-1.505.007t-.533-1.408l.143-.572q.119-.474-.267-.774l-.353-.275q-.705-.548-.451-1.403t1.144-.929l.623-.052q.478-.04.642-.491l.172-.473q.307-.844 1.205-.844t1.205.844");
}

</style>

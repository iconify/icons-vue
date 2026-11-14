<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzlno_l2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chore-reminder" /></template>
<style>
.lzlno_l2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.19 17H3.5L5 15.5V10q0-.147.007-.294q.007-.148.022-.294q.014-.147.036-.292q.022-.146.05-.291q.029-.144.065-.287t.078-.284t.093-.279q.049-.139.106-.275t.119-.269t.132-.263t.146-.257t.157-.248q.082-.123.17-.241q.087-.119.181-.232q.093-.114.192-.223t.203-.214q.105-.104.214-.203t.223-.192t.232-.181t.241-.17t.248-.157q.127-.076.257-.146t.263-.132t.269-.119t.275-.106t.279-.093q.141-.042.284-.078t.287-.065t.291-.05q.145-.022.292-.036q.146-.015.294-.022Q10.853 4 11 4t.294.007t.294.022q.147.014.292.036q.146.022.291.05q.144.029.287.065t.284.078t.279.093q.139.049.275.106t.269.119t.263.132t.257.146q.126.075.248.157q.123.082.241.17q.119.087.232.181q.114.093.223.192t.214.203q.104.105.203.214t.192.223t.181.232t.17.241t.157.248q.076.127.146.257t.132.263t.119.269t.106.275t.093.279t.078.284q.036.143.065.287q.028.145.05.291q.022.145.036.292q.015.146.022.294Q17 9.853 17 10v2.131M11 2.5V4m0 13a2 2 0 0 1 0 4m7-6.25v3.5M18 21h.01");
}

</style>

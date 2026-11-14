<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-tl2lb2i"/><path class="gvpxmn2na"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gps-waypoint" /></template>
<style>
.gvpxmn2na {
  d: path("M7 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m9.5 6v6.5m0-6.5h5L20 17.25l1.5 2.25h-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-tl2lb2i {
  d: path("M13.741 14.801c-1.227 2.142-2.882 4.068-4.241 5.699c-2.5-3-6-7-6-11.5q0-.147.007-.294q.007-.148.022-.294q.014-.147.036-.292q.022-.146.05-.291q.029-.144.065-.287t.078-.284q.043-.141.093-.279q.049-.139.106-.275t.119-.269t.132-.263t.146-.257t.157-.248q.082-.123.17-.241q.087-.119.181-.232q.093-.114.192-.223t.203-.214q.105-.104.214-.203t.223-.192t.232-.181t.241-.17t.248-.157q.127-.076.257-.146t.263-.132t.269-.119t.275-.106q.138-.05.279-.093t.284-.078q.143-.036.287-.065q.145-.028.291-.05q.145-.022.292-.036q.146-.015.294-.022Q9.353 3 9.5 3t.294.007t.294.022t.292.036t.291.05q.144.029.287.065t.284.078q.141.043.279.093q.139.049.275.106t.269.119t.263.132t.257.146t.248.157q.123.082.241.17q.119.087.232.181q.114.093.223.192t.214.203q.104.105.203.214t.192.223t.181.232t.17.241t.157.248q.076.127.146.257t.132.263t.119.269t.106.275q.05.138.093.279t.078.284t.065.287q.028.145.05.291q.022.145.036.292q.015.146.022.294q.007.147.007.294c0 1.354-.317 2.663-.828 3.914");
}

</style>

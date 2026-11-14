<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b3s_8rihw"/><path class="a_t2aabhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:intellectual-property" /></template>
<style>
.a_t2aabhm {
  d: path("M19.25 17.25a1.5 1.5 0 1 0 0 2");
}

.b3s_8rihw {
  d: path("M12.328 16H7.5v-1.5c0-1.5-3.5-3-3.5-6q0-.147.007-.294q.007-.148.022-.294q.014-.147.036-.292q.022-.146.05-.291q.029-.144.065-.287t.078-.284t.093-.279q.049-.139.106-.275t.119-.269t.132-.263t.146-.257t.157-.248q.082-.123.17-.241q.087-.119.181-.232q.093-.114.192-.223t.203-.214q.105-.104.214-.203t.223-.192t.232-.181t.241-.17t.248-.157q.127-.076.257-.146t.263-.132t.269-.119t.275-.106t.279-.093q.141-.042.284-.078t.287-.065t.291-.05q.145-.022.292-.036q.146-.015.294-.022Q9.853 2.5 10 2.5t.294.007t.294.022t.292.036t.291.05q.144.029.287.065t.284.078q.141.043.279.093q.139.049.275.106t.269.119t.263.132t.257.146t.248.157q.123.082.241.17q.119.087.232.181q.114.093.223.192t.214.203q.104.105.203.214t.192.223t.181.232t.17.241t.157.248q.076.127.146.257t.132.263t.119.269t.106.275q.05.138.093.279t.078.284t.065.287q.028.145.05.291q.022.145.036.292q.015.146.022.294q.007.147.007.294c0 3-3.5 4.5-3.5 6v1.172M8 19h4m2.75-.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

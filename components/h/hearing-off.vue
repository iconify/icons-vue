<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xh-x_2lgk"/><path class="r030r9ble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hearing-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r030r9ble {
  d: path("M10.623 6.659q.198-.158.421-.282t.461-.207q.24-.085.491-.127Q12.246 6 12.5 6q.147 0 .294.014t.291.044q.145.028.286.071t.277.099q.136.057.266.126q.13.07.253.152q.122.081.236.175t.218.198q.105.104.198.218t.175.236q.082.123.152.253t.126.266t.099.277t.071.286t.044.291T15.5 9c0 .781-.339 1.291-.84 1.706M3.5 3.5l17 17");
}

.xh-x_2lgk {
  d: path("M8.499 4.528q.409-.366.878-.651t.982-.482t1.052-.295q.54-.1 1.089-.1q.147 0 .294.007q.148.007.294.022q.147.014.292.036q.146.022.291.05q.144.029.287.065t.284.078q.141.043.279.093q.139.049.275.106t.269.119t.263.132t.257.146t.248.157q.123.082.241.17q.119.087.232.181q.114.093.223.192t.214.203q.104.105.203.214t.192.223q.094.113.181.232q.088.118.17.241q.082.122.157.248q.076.127.146.257t.132.263t.119.269t.106.275q.05.138.093.279t.078.284q.036.143.065.287q.028.145.05.291q.022.145.036.292q.015.146.022.294q.007.147.007.294c0 1.784-.753 2.965-1.557 4.04m-2.731 5.186c-.722 1.252-1.785 2.274-3.462 2.274c-2 0-3.25-1.25-3.75-2.75");
}

</style>

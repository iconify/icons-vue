<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vn-6zzh-f"/><path class="ecwgwqbhc"/><path class="hrqohn1pc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-broken" /></template>
<style>
.ecwgwqbhc {
  d: path("M9.5 18.5H14.5");
}

.hrqohn1pc {
  stroke-linejoin: round;
  d: path("M12 6.75H12.0001");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vn-6zzh-f {
  d: path("M4.35294 15.5357V8C4.35294 6.11438 4.35294 5.17157 4.93873 4.58579C5.52451 4 6.46732 4 8.35294 4M4.35294 15.5357L2.60888 17.3358C2.56438 17.3818 2.54208 17.4048 2.52127 17.4276C2.20022 17.7802 2.01569 18.2358 2.00096 18.7124C2 18.7433 2 18.7753 2 18.8393C2 18.9885 2 19.0631 2.00398 19.1261C2.06749 20.1314 2.86865 20.9325 3.87388 20.996C3.93688 21 4.01148 21 4.16068 21H19.8393C19.9885 21 20.0631 21 20.1261 20.996C21.1314 20.9325 21.9325 20.1314 21.996 19.1261C22 19.0631 22 18.9885 22 18.8393C22 18.7753 22 18.7433 21.999 18.7124C21.9843 18.2358 21.7998 17.7802 21.4787 17.4276C21.4579 17.4048 21.4356 17.3818 21.3911 17.3358L19.6471 15.5357M4.35294 15.5357H13M19.6471 15.5357V8C19.6471 6.11438 19.6471 5.17157 19.0613 4.58579C18.4755 4 17.5327 4 15.6471 4H12M19.6471 15.5357H17.0357");
}

</style>

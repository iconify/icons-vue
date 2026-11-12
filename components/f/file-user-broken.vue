<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0cmz0boh"/><circle class="tvwvv6hyt"/><path class="vve12wqxb"/><path class="t4qaumccy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-user-broken" /></template>
<style>
.e0cmz0boh {
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t4qaumccy {
  stroke-linejoin: round;
  d: path("M2 10V14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18M22 14V13.5629C22 11.8083 22 10.931 21.654 10.1541C21.308 9.3772 20.6559 8.79032 19.3517 7.61654L15.3929 4.05365C14.2651 3.03857 13.7012 2.53104 13.0092 2.26552C12.3173 2 11.5548 2 10.0298 2C6.23869 2 4.34315 2 3.17157 3.17157C2.51839 3.82475 2.22937 4.69989 2.10149 6");
}

.tvwvv6hyt {
  cx: 9.25px;
  cy: 12.592px;
  r: 1.375px;
}

.vve12wqxb {
  d: path("M12.0001 16.7167C12.0001 17.476 12.0001 18.0916 9.25029 18.0916C6.50049 18.0916 6.50049 17.476 6.50049 16.7167C6.50049 15.9574 7.73162 15.3418 9.25029 15.3418C10.769 15.3418 12.0001 15.9574 12.0001 16.7167Z");
}

</style>

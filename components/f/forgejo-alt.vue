<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m_1nxvwab"/><path class="lz6tdkb8p"/><path class="pw3h6_bwy"/><circle class="z7lxhjboe"/><circle class="hlxw9cbzi"/><circle class="qknsy_bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forgejo-alt" /></template>
<style>
.hlxw9cbzi {
  cx: 31.903px;
  cy: 21.363px;
  r: 1.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lz6tdkb8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.202 17.675c0-5.698 5.27-6.652 10.172-6.652");
}

.m_1nxvwab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.202 35.633a4.216 4.216 0 1 1-4.762.375m14.816-16.753a4.216 4.216 0 1 1 .375 4.762m-.143-17.778a4.216 4.216 0 1 1-.124 4.773m-.108 8.243h-4.254m4.612 4.743H24m-10.54-6.323V35.99m4.742-5.669v5.308");
}

.pw3h6_bwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.46 17.675c0-7.179 4.742-11.393 14.912-11.393m-4.374 17.716c-3.162 0-5.796 2.834-5.796 6.323m5.796-11.066c-5.796 0-10.539 4.743-10.539 10.54m4.743-12.12v3.33");
}

.qknsy_bsn {
  cx: 16.094px;
  cy: 39.28px;
  r: 1.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z7lxhjboe {
  cx: 31.903px;
  cy: 8.716px;
  r: 1.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

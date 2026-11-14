<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdw7sebey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyewear-kiosk" /></template>
<style>
.sdw7sebey {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.311 6.205l19.439.274v.022q-.002 2.997-3 2.997q-1.499 0-2.249-.749q-.75.751-2.251.751T12 8.75q-.75.75-2.25.75t-2.251-.751q-.75.75-2.249.75q-2.999 0-3-2.999q0-.154.061-.295M3.75 16q0-1.553 1.098-2.652Q5.947 12.25 7.5 12.25q2.81 0 3.514 2.106q.986-.374 1.972 0q.704-2.106 3.514-2.106q3.75 0 3.75 3.75t-3.75 3.75T12.75 16l.001-.093q-.751-.402-1.502 0l.001.093q0 3.75-3.75 3.75T3.75 16");
}

</style>

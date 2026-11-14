<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah1cqdztk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loose-chippings-sign" /></template>
<style>
.ah1cqdztk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.407 15.701L14.93 6.116q-.972-1.7-2.93-1.7t-2.93 1.7l-5.477 9.585q-.964 1.687.011 3.368q.976 1.681 2.919 1.681h10.954q1.943 0 2.919-1.681q.975-1.681.011-3.368M18.75 8.5q0-1.75 1.75-1.75t1.75 1.75t-1.75 1.75t-1.75-1.75M13 10.75q1.75 0 1.75 1.75T13 14.25t-1.75-1.75T13 10.75M7.25 16q0-1.75 1.75-1.75T10.75 16T9 17.75T7.25 16");
}

</style>

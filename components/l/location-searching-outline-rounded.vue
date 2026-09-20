<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu5pm-b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-searching-outline-rounded" /></template>
<style>
.nu5pm-b_r {
  fill: currentColor;
  d: path("M11.5 21v-.961q-3.125-.293-5.16-2.329t-2.328-5.16H3.05q-.213 0-.357-.143t-.143-.357t.143-.357t.357-.143h.962q.292-3.125 2.328-5.16t5.16-2.328V3.1q0-.213.143-.357T12 2.6t.357.143t.143.357v.962q3.125.292 5.16 2.328t2.329 5.16h.961q.214 0 .357.143t.143.357t-.143.357t-.357.143h-.961q-.293 3.125-2.328 5.16q-2.036 2.036-5.161 2.328V21q0 .214-.143.357T12 21.5t-.357-.143T11.5 21m5.45-4Q19 14.95 19 12.05T16.95 7.1T12 5.05T7.05 7.1T5 12.05T7.05 17T12 19.05T16.95 17");
}

</style>

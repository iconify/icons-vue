<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pipfeq4wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:disc-full-rounded" /></template>
<style>
.pipfeq4wl {
  fill: currentColor;
  d: path("M14.178 14.486Q15.192 13.47 15.192 12t-1.014-2.485T11.692 8.5q-1.47 0-2.485 1.015T8.192 12t1.015 2.486t2.485 1.014t2.486-1.014m-3.198-1.774q-.288-.287-.288-.712t.288-.712t.712-.288t.713.288t.287.712t-.287.713t-.713.287t-.712-.288m9.356 5.145q-.144-.143-.144-.357V11q0-.213.144-.357t.356-.143t.357.143t.143.357v6.5q0 .214-.143.357t-.357.143t-.356-.143m-.077 2.615q-.182-.181-.182-.433t.182-.434t.433-.182t.434.182t.182.434t-.182.433t-.434.182t-.433-.182M11.692 21q-1.863 0-3.505-.71q-1.643-.711-2.858-1.926q-1.215-1.216-1.926-2.858T2.693 12t.71-3.506t1.926-2.857T8.187 3.71Q9.829 3 11.692 3q2.402 0 4.43 1.155q2.026 1.154 3.247 3.14q.248.397.006.801t-.727.404h-.11q-.136 0-.241.105q-.105.104-.105.241v8.775q0 .254-.095.484t-.293.41q-1.244 1.16-2.821 1.823q-1.577.662-3.29.662");
}

</style>

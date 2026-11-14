<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sos7so20x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lead-warm" /></template>
<style>
.sos7so20x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7M17 12.5v4.653l-.049.048q-.952.952-.951 2.298v.002q-.001 1.346.951 2.298q.952.953 2.299.953t2.299-.953t.951-2.3q.001-1.345-.951-2.298l-.049-.048V12.5q0-2.25-2.25-2.25T17 12.5m2.25 3.748q-.392 0-.75.081V12.5q0-.75.75-.75t.75.75v3.829q-.358-.081-.75-.081m-3.5.417V14.57q-2.175-1.32-5.25-1.32q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h11.088q-.338-.804-.338-1.749v-.002q0-1.624 1-2.834m2.5 1.394q.436-.311 1-.311t1 .311q.043.039.093.071q.074.061.145.131q.512.513.512 1.24q.001.725-.512 1.238t-1.238.513t-1.238-.513q-.512-.513-.512-1.238v-.002q-.001-.725.512-1.238q.071-.07.145-.131q.05-.032.093-.071");
}

</style>

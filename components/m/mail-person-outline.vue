<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0eg8uvdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-person-outline" /></template>
<style>
.v0eg8uvdb {
  fill: currentColor;
  d: path("M4 6v12v-7.808v.39zm8.154 13H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v3.576h-1V6.904l-8 5.212l-8-5.212v10.48q0 .27.173.443t.443.173h7.538zm5.615-3.423q-.632 0-1.066-.434t-.434-1.066t.434-1.066t1.066-.434t1.067.434t.433 1.066t-.433 1.066q-.434.434-1.067.434M14.54 19v-.171q0-.427.219-.764q.219-.336.62-.529q.566-.275 1.162-.405q.595-.131 1.247-.131q.629 0 1.223.13q.594.132 1.13.407q.402.198.631.531q.229.334.229.76V19zM12 11l7.692-5H4.308z");
}

</style>

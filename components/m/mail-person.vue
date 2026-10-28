<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdg0hjbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-person" /></template>
<style>
.kdg0hjbar {
  fill: currentColor;
  d: path("M17.77 15.577q-.634 0-1.067-.434q-.434-.433-.434-1.066t.434-1.066t1.066-.434t1.067.434t.433 1.066t-.433 1.066t-1.067.434M14.54 19v-.171q0-.427.219-.764q.219-.336.62-.529q.566-.275 1.162-.405q.595-.131 1.247-.131q.629 0 1.223.13q.594.132 1.13.407q.402.198.631.531q.229.334.229.76V19zm-3.65 0H4.615q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v3.686q-.735-.383-1.542-.583t-1.683-.2q-.644 0-1.27.115q-.624.114-1.205.343L20 6.904L19.692 6L12 11L4.308 6L4 6.904l8 5.212l.546-.352q-.95.977-1.491 2.259t-.541 2.758q0 .588.104 1.134q.105.545.27 1.085");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msk5rgejw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-person-outline-sharp" /></template>
<style>
.msk5rgejw {
  fill: currentColor;
  d: path("M4 6v12v-7.808v.39zM3 19V5h18v5.192h-1V6.904l-8 5.212l-8-5.212V18h8.154v1zm14.77-3.423q-.634 0-1.067-.434q-.434-.434-.434-1.066t.434-1.066t1.066-.434t1.067.434t.433 1.066t-.433 1.066q-.434.434-1.067.434M14.54 19v-.171q0-.427.219-.764q.219-.336.62-.529q.566-.275 1.162-.405q.595-.131 1.247-.131q.629 0 1.223.13q.594.132 1.13.407q.402.198.631.531q.229.334.229.76V19zM12 11l7.692-5H4.308z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvw4adb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-clock-outline" /></template>
<style>
.yvw4adb8x {
  fill: currentColor;
  d: path("M5 9.615h14v-3q0-.23-.192-.423T18.384 6H5.616q-.231 0-.424.192T5 6.616zm0 0V6zM5.616 21q-.691 0-1.153-.462T4 19.385V6.615q0-.69.463-1.152T5.616 5h1.769V2.77h1.077V5h7.154V2.77h1V5h1.769q.69 0 1.153.463T20 6.616v5.251q-.244-.09-.494-.134T19 11.652v-1.036H5v8.769q0 .23.192.423t.423.192h6.704q.079.28.201.521q.122.24.255.479zm9.933-.164Q14.385 19.67 14.385 18t1.164-2.835T18.384 14q1.672 0 2.836 1.165q1.165 1.164 1.165 2.835t-1.165 2.836T18.385 22t-2.836-1.164m4.492-.634l.546-.546l-1.818-1.818v-2.722H18v3.046z");
}

</style>

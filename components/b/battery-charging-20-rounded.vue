<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl84f585a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-20-rounded" /></template>
<style>
.pl84f585a {
  fill: currentColor;
  d: path("M8.692 21q-.343 0-.575-.232t-.233-.576V5.288q0-.343.233-.575t.575-.232h1.616v-.673q0-.344.232-.576T11.116 3h1.769q.343 0 .575.232t.232.576v.673h1.62q.344 0 .574.232t.23.575v6.27q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356V5.462H8.885v12.48h1.532q.287 0 .474.194q.186.193.217.485q.056.377.142.734q.086.356.22.695q.142.348-.049.649q-.19.301-.538.301zm7.885-2.154h-.858q-.223 0-.341-.195t-.001-.407l1.676-3.021q.083-.127.227-.096t.143.197v1.83h.858q.223 0 .341.195t.001.407l-1.676 3.021q-.084.127-.227.096t-.143-.197z");
}

</style>

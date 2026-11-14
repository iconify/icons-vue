<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0drtzovc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boombox" /></template>
<style>
.z0drtzovc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.005 7.495q-.971-.971-2.255-1.185V5q0-2.25-2.25-2.25h-9Q5.25 2.75 5.25 5v1.31q-1.284.214-2.255 1.185Q1.75 8.74 1.75 10.5v6q0 1.76 1.245 3.005T6 20.75h12q1.76 0 3.005-1.245T22.25 16.5v-6q0-1.76-1.245-3.005M6.75 5q0-.75.75-.75h9q.75 0 .75.75v1.25H6.75zm-1.902 6.348Q5.947 10.25 7.5 10.25q3.75 0 3.75 3.75T7.5 17.75T3.75 14q0-1.553 1.098-2.652M12.75 14q0-3.75 3.75-3.75T20.25 14t-3.75 3.75T12.75 14");
}

</style>

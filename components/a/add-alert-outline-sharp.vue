<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7x6j5boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-alert-outline-sharp" /></template>
<style>
.z7x6j5boo {
  fill: currentColor;
  d: path("M5 18.77v-1h1.616V9.845q0-1.96 1.24-3.447T11 4.546V3h2v1.546q1.904.366 3.144 1.853t1.24 3.447v7.923H19v1zm6.997 2.615q-.668 0-1.14-.475t-.472-1.14h3.23q0 .67-.475 1.142q-.476.472-1.143.472M7.616 17.77h8.769V9.846q0-1.823-1.281-3.104T12 5.462t-3.104 1.28t-1.28 3.104zm3.884-3.153h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>

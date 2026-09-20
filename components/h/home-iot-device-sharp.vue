<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj0z73beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-iot-device-sharp" /></template>
<style>
.wj0z73beo {
  fill: currentColor;
  d: path("M5.025 10h1V6.5q0-.225-.137-.363T5.525 6t-.363.138t-.137.362zm.5 10q-1.875 0-3.187-1.3t-1.313-3.2q0-1.2.55-2.15t1.45-1.55V6.5q0-1.05.725-1.775T5.525 4t1.775.725t.725 1.775v5.3q.9.6 1.45 1.55t.55 2.15q0 1.875-1.312 3.188T5.525 20m8.175-5q-1.2-.825-1.95-2.125T11 10q0-2.5 1.75-4.25T17 4t4.25 1.75T23 10q0 1.575-.75 2.875T20.3 15zm2.25 4.55q-.45-.45-.45-1.05h3q0 .6-.45 1.05T17 20t-1.05-.45M14 18v-2h6v2z");
}

</style>

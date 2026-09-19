<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="drqtsoz6o"/><path class="mp7nwgbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hemul-chatgpt" /></template>
<style>
.drqtsoz6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.06 3.5c.274 3.67-2.069 6.433-4.949 8.493c-17.475 10.759-9.899 28.848.361 31.347c.625.196 4.51.762 2.763-.195c-4.198-2.01-4.988-5.428-1.63-9.46c7.614-7.292 9.206-14.77 7.42-21.819c.194 7.38-4.794 14.4-11.647 14.449c-5.36-6.111 7.927-11.393 8.669-18.383c.205-1.67-.313-2.958-.977-4.432z");
}

.mp7nwgbwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.811 14.366c-1.406 1.034-2.782 2.108-4.198 3.133c-1.747 1.64-3.416 3.26-4.627 5.34c-5.106 11.52 2.655 18.598 7.244 20.58c1.376.741 4.305 1.288 6.13 1.005c.684-.088.84-.4 1.406-.4");
}

</style>

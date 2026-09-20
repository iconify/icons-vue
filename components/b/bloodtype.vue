<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op78kd3jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bloodtype" /></template>
<style>
.op78kd3jc {
  fill: currentColor;
  d: path("M6.999 18.937Q5 16.873 5 13.8q0-2.154 1.738-4.765T12 3.308q3.525 3.117 5.262 5.728Q19 11.646 19 13.8q0 3.073-2.002 5.137Q14.994 21 11.996 21t-4.998-2.064M9.5 17.5h5v-1h-5zm2-3h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>

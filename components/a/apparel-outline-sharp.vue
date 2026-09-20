<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrbrmwbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:apparel-outline-sharp" /></template>
<style>
.lrbrmwbms {
  fill: currentColor;
  d: path("m6 10.95l-1.875 1.025l-2.975-5.2L7.75 3H10v1q0 .825.588 1.413T12 6t1.413-.587T14 4V3h2.25l6.6 3.775l-2.95 5.15l-1.9-.95V21H6zM8 7.6V19h8V7.6l3.1 1.7l1.05-1.75l-4.3-2.5q-.375 1.275-1.412 2.113T12 8t-2.437-.837T8.15 5.05l-4.3 2.5L4.9 9.3zm4 4.425");
}

</style>

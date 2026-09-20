<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7uqvz70c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:apparel-sharp" /></template>
<style>
.v7uqvz70c {
  fill: currentColor;
  d: path("m6 10.95l-1.875 1.025l-2.975-5.2L7.75 3H10v1q0 .825.588 1.413T12 6t1.413-.587T14 4V3h2.25l6.6 3.775l-2.95 5.15l-1.9-.95V21H6z");
}

</style>

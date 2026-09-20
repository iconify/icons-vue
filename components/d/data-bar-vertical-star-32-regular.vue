<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tp5hc0bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-star-32-regular" /></template>
<style>
.tp5hc0bst {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M6.5 15a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 1 1-7 0v-7A3.5 3.5 0 0 1 6.5 15m9-6a3.5 3.5 0 0 1 3.5 3.5v2.438c-.728.361-1.4.818-2 1.355V12.5a1.5 1.5 0 0 0-3 0v13c0 .602.355 1.12.867 1.358a9 9 0 0 0 1.36 2.065q-.353.076-.727.077a3.5 3.5 0 0 1-3.5-3.5v-13A3.5 3.5 0 0 1 15.5 9m8.212 9.139c-.228-.685-1.196-.685-1.424 0l-.94 2.827h-2.994c-.731 0-1.03.938-.434 1.361l2.406 1.707l-.928 2.791c-.23.688.554 1.268 1.145.849L23 25.93l2.457 1.743c.591.42 1.374-.161 1.145-.849l-.928-2.79l2.406-1.708c.596-.423.297-1.361-.433-1.361h-2.995zM6.5 17A1.5 1.5 0 0 0 5 18.5v7a1.5 1.5 0 0 0 3 0v-7A1.5 1.5 0 0 0 6.5 17m18-14A3.5 3.5 0 0 1 28 6.5v9.016a9 9 0 0 0-2-1.002V6.5a1.5 1.5 0 0 0-3 0V14c-.688 0-1.357.08-2 .226V6.5A3.5 3.5 0 0 1 24.5 3");
}

</style>

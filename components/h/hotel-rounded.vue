<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqprxt7pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hotel-rounded" /></template>
<style>
.vqprxt7pp {
  fill: currentColor;
  d: path("M2.5 18q-.214 0-.357-.144T2 17.5v-12q0-.213.144-.356T2.501 5t.356.144T3 5.5V14h8.5V8q0-.402.299-.701T12.5 7H19q1.238 0 2.119.881T22 10v7.5q0 .213-.144.356t-.357.144t-.356-.144T21 17.5V15H3v2.5q0 .213-.144.356T2.499 18M5.5 11.498q-.615-.618-.615-1.5T5.502 8.5t1.5-.615t1.498.617t.616 1.5t-.618 1.498t-1.5.616t-1.498-.618");
}

</style>

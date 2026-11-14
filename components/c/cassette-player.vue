<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lii2o3xhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cassette-player" /></template>
<style>
.lii2o3xhi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 3.25h-11q-1.76 0-3.005 1.245T1.25 7.5v6q0 1.76 1.245 3.005T5.5 17.75h8v-.232q0-1.989 1.709-3.007q1.708-1.017 3.457-.071l.001.001l1.351.732q.166.089.317.188q.415-.844.415-1.861v-6q0-1.76-1.245-3.005T16.5 3.25M7 7q3 0 3 3q0 .879-.257 1.5h2.514Q12 10.879 12 10q0-3 3-3t3 3t-3 3H7q-3 0-3-3t3-3m11.071 8.54l1.351.732q1.179.638 1.179 1.978t-1.179 1.979l-1.351.731q-1.124.609-2.223-.045q-1.098-.655-1.098-1.933v-1.464q0-1.278 1.098-1.933q1.099-.654 2.223-.046zm-.714 1.319v-.001q-.375-.202-.741.016t-.366.644v1.464q0 .426.366.644t.741.016l1.351-.732q.393-.213.393-.66t-.393-.66z");
}

</style>

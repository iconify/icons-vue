<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="equ643raw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:connecting-rod" /></template>
<style>
.equ643raw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 6.5q0-1.76 1.245-3.005T6.5 2.25t3.005 1.245T10.75 6.5q0 1.373-.757 2.432l2.502 2.503Q14.002 10.25 16 10.25q2.382 0 4.066 1.684T21.75 16t-1.684 4.066T16 21.75t-4.066-1.684T10.25 16q0-1.998 1.185-3.505L8.932 9.993q-1.059.757-2.432.757q-1.76 0-3.005-1.245T2.25 6.5m2.25 0q0 2 2 2q.828 0 1.414-.586T8.5 6.5t-.586-1.414T6.5 4.5q-2 0-2 2M16 13q-3 0-3 3t3 3q1.243 0 2.121-.879Q19 17.243 19 16t-.879-2.121Q17.243 13 16 13");
}

</style>

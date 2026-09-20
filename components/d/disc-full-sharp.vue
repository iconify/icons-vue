<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7wcyb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:disc-full-sharp" /></template>
<style>
.yn7wcyb5g {
  fill: currentColor;
  d: path("M11.692 21q-1.867 0-3.51-.708t-2.857-1.924T3.4 15.512t-.709-3.509t.709-3.51t1.924-2.859t2.857-1.925T11.692 3q2.732 0 4.985 1.493t3.32 4.007h-1.805v9.654q-1.286 1.335-2.965 2.09q-1.679.756-3.535.756m2.486-6.514Q15.192 13.47 15.192 12t-1.014-2.485T11.692 8.5q-1.47 0-2.485 1.015T8.192 12t1.015 2.486t2.485 1.014t2.486-1.014m-3.198-1.774q-.288-.287-.288-.712t.288-.712t.712-.288t.713.288t.287.712t-.287.713t-.713.287t-.712-.288m9.279 7.76q-.182-.181-.182-.433t.182-.434t.433-.182t.434.182t.182.434t-.182.433t-.434.182q-.251 0-.433-.182M20.192 18v-7.5h1V18z");
}

</style>

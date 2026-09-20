<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udumdub5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:linear-scale" /></template>
<style>
.udumdub5j {
  fill: currentColor;
  d: path("M17.154 16.308q-1.666 0-2.848-1.051T12.869 12.5H6.685q-.166.675-.704 1.145t-1.327.47q-.877 0-1.496-.619T2.538 12t.62-1.496t1.496-.62q.788 0 1.327.47t.704 1.146h6.184q.254-1.706 1.437-2.757t2.848-1.05q1.787 0 3.047 1.279q1.26 1.28 1.26 3.067q0 1.747-1.26 3.008t-3.047 1.26m2.337-1.97q.97-.972.97-2.337t-.97-2.336t-2.337-.972t-2.337.971t-.97 2.337t.97 2.337t2.337.97t2.337-.97");
}

</style>

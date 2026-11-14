<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyh69ob_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:image" /></template>
<style>
.dyh69ob_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 3.25h11q1.76 0 3.005 1.245T21.75 7.5v9q0 1.76-1.245 3.005T17.5 20.75h-1q.149 0 .287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-8.5-8.5q-.105-.106-.243-.163T8 10.75t-.287.057t-.243.163l-5 5q-.106.105-.163.243q-.057.137-.057.286V7.5q0-1.76 1.245-3.005T6.5 3.25m10 17.5h-10q-1.76 0-3.005-1.245q-1.245-1.244-1.245-3.004q0 .149.057.286q.057.138.163.243q.105.106.243.163T3 17.25t.287-.057t.243-.163L8 12.561l7.97 7.969q.105.106.243.163t.287.057M13.25 9q0 2.25 2.25 2.25T17.75 9T15.5 6.75T13.25 9");
}

</style>

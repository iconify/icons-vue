<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq917cbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dermatoscope" /></template>
<style>
.iq917cbyl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.373 4.373Q2.25 6.497 2.25 9.5t2.123 5.127T9.5 16.75q1.944 0 3.52-.89q.089.783.872 1.566l3.182 3.183q1.767 1.765 3.535-.001q1.765-1.767-.001-3.534l-3.182-3.183q-.783-.782-1.566-.871q.89-1.576.89-3.52q0-3.003-2.123-5.127T9.5 2.25q-3.003 0-5.127 2.123M4.75 9.5q0-1.968 1.391-3.359T9.5 4.75t3.359 1.391T14.25 9.5t-1.391 3.359T9.5 14.25t-3.359-1.391T4.75 9.5m1.5 0q0-3.25 3.25-3.25t3.25 3.25t-3.25 3.25T6.25 9.5m1.25 0q0-2 2-2t2 2t-2 2t-2-2");
}

</style>

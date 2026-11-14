<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7llb-zfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cat-cave" /></template>
<style>
.u7llb-zfp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.752 17.999Q2.898 2.75 12 2.75t9.248 15.249q1.002.499 1.002 2.001q0 2.25-2.25 2.25H4q-2.25 0-2.25-2.25q0-1.502 1.002-2.001m16.992-.249Q19.543 4.25 12 4.25t-7.744 13.5H7.25V14q0-1.968 1.391-3.359T12 9.25t3.359 1.391T16.75 14v3.75zm-4.494 0V14q0-3.25-3.25-3.25T8.75 14v3.75z");
}

</style>

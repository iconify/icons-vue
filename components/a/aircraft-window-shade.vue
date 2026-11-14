<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_zsiccde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aircraft-window-shade" /></template>
<style>
.f_zsiccde {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.48 4.02Q15.21 1.75 12 1.75T6.52 4.02T4.25 9.5v5q0 3.21 2.27 5.48T12 22.25t5.48-2.27t2.27-5.48v-5q0-3.21-2.27-5.48M12 4.75q1.968 0 3.359 1.391T16.75 9.5v5q0 1.968-1.391 3.359T12 19.25t-3.359-1.391T7.25 14.5v-5q0-1.968 1.391-3.359T12 4.75");
}

</style>

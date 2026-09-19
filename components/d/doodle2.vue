<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdi35vbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doodle2" /></template>
<style>
.zdi35vbqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.849 16.718l3.826 7.652a3.35 3.35 0 0 1-1.149 4.215l-22.197 10.72a3.03 3.03 0 0 1-4.09-1.27q-.07-.131-.125-.269l-9.03-18.304a7.862 7.862 0 0 1 13.558-7.966l14.612 30.865m1.148-36.722a3.807 3.807 0 1 1-3.807 3.807a3.8 3.8 0 0 1 3.807-3.807");
}

</style>

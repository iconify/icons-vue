<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvqe-2qov"/><path class="wwgo73sqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audiofx" /></template>
<style>
.rvqe-2qov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.304 12.934l7.627-7.617l3.798 3.798l-7.647 7.597Zm5.788 2.158a15.845 15.845 0 0 1-2.087 20.323l3.928 4.069a21.5 21.5 0 0 0 2.224-28.425");
}

.wwgo73sqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.997 10.974a15.845 15.845 0 0 0-20.002 24.441l-3.928 4.069A21.5 21.5 0 0 1 37.034 6.918");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxr82_0am"/><path class="k58grzbmi"/><circle class="kmq3z3bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-camera-with-flash" /></template>
<style>
.k58grzbmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.354 18.316l-5.508 6.409l6.749-3.65l.893 8.22l2.63-7.539l4.616 2.78l-3.672-5.984l6.302-3.676l-7.742 2.12l-.694-7.115l-2.085 6.786l-6.997-2.875zm22.186 7.092h8.31m-20.51 2.929a3.333 3.333 0 0 0 6.666.004v-.004a3.333 3.333 0 1 0-6.666 0");
}

.kmq3z3bsx {
  cx: 24.673px;
  cy: 28.337px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mxr82_0am {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.189 22.376v13.701c0 1.128.938 2.042 2.096 2.042h27.773c1.158 0 2.096-.914 2.096-2.042v-15.48c0-1.128-.938-2.042-2.096-2.042H17.063");
}

</style>

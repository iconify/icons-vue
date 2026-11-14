<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdtrsrbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:karaoke-mic-play" /></template>
<style>
.fdtrsrbhy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.434 3.934Q7.75 5.618 7.75 8q0 1.345.537 2.467q-.527.213-1.054.74l-4.027 4.026Q1.441 17 3.207 18.767l.026.027Q5 20.559 6.767 18.793l4.027-4.026q.657-.658.825-1.315q.879.298 1.881.298q2.382 0 4.066-1.684T19.25 8t-1.684-4.066T13.5 2.25T9.434 3.934m8.7 11.734l1.523.888q1.117.651 1.117 1.944t-1.117 1.944l-1.523.888q-1.125.656-2.255.007q-1.129-.648-1.129-1.951v-1.776q0-1.303 1.129-1.951t2.255.007m-.756 1.296q-.375-.219-.752-.003q-.376.217-.376.651v1.776q0 .434.376.651q.377.216.752-.003l1.523-.888q.373-.217.373-.648t-.373-.648z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fh9dsy0pk"/><rect transform="rotate(-45 34.183 34.189)" class="he8qx7bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imagesearchman" /></template>
<style>
.fh9dsy0pk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.108 9.237c4.962 4.962 4.988 12.98.051 17.917c-4.936 4.936-12.954 4.91-17.916-.051s-4.987-12.98-.051-17.917s12.955-4.91 17.916.051m.052 17.917l1.355 1.355");
}

.he8qx7bdw {
  width: 8.872px;
  height: 16.05px;
  x: 29.748px;
  y: 26.164px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.208px;
  ry: 1.208px;
}

</style>

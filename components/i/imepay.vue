<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="xbspsubzy"/><path class="me21jnb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imepay" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.me21jnb1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.753 27.237v4.537a2.75 2.75 0 1 1-5.5 0v-4.537m-2.503 4.537a2.75 2.75 0 1 1-5.5 0v-1.787a2.75 2.75 0 1 1 5.5 0m0 4.537v-7.287m-13.503 4.537a2.75 2.75 0 1 0 5.5 0v-1.787a2.75 2.75 0 1 0-5.5 0m0-2.75v11");
}

.xbspsubzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.366 20.24l2.96 2.854a.53.53 0 0 0 .833-.12l7.09-12.668L16.163 14a.53.53 0 0 0-.251.896l3.964 3.874l7.677-5.107l-7.677 5.107zl-2.364 1.93a.415.415 0 0 1-.678-.322v-4.573m16.429 14.499v3.713a2.75 2.75 0 0 1-2.75 2.75c-.76 0-1.447-.308-1.945-.806");
}

</style>

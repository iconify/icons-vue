<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o0l_t8bwn"/><circle class="ecx9q7bgc"/><circle class="a7x-x35hq"/><path class="y59-r41zn"/><path class="vkk34981j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gbcemu" /></template>
<style>
.a7x-x35hq {
  cx: 32.163px;
  cy: 26.869px;
  r: 1.543px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ecx9q7bgc {
  cx: 27.209px;
  cy: 27.639px;
  r: 1.543px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o0l_t8bwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.978 5.46c-1.21 1.045-.964 5.157-1.07 7.77c-.083 2.079.45 4.153.35 6.232c-.1 2.099-.814 4.136-.95 6.232c-.271 4.2-.293 7.17.28 12.62c.57 5.435 8.27 5.184 12.412 5.184s11.843.251 12.413-5.184c.572-5.45.55-8.42.278-12.62c-.136-2.096-.85-4.133-.95-6.232c-.099-2.079.434-4.153.35-6.233c-.105-2.612.141-6.724-1.069-7.77c-1.207-1.042-2.977-.957-11.002-.957s-9.835-.085-11.043.958Zm4.988 20.619v1.24m0 3.851v1.239m-3.169-3.165h1.241m3.856 0h1.24");
}

.vkk34981j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.546 19.93V9.981H18.454v9.947z");
}

.y59-r41zn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.877 32.629l2.688-.428m-7.799.895l2.736-.135m-1.1-9.894c4.863-.26 6.053-1.59 6.132-7.337c.08-5.747.3-7.983-2.19-8.142S26.449 7.47 24 7.47s-4.855-.04-7.345.12c-2.49.158-2.269 2.394-2.19 8.14c.08 5.748 1.27 7.078 6.133 7.338c1.285.07 2.267.112 3.402.112s2.117-.043 3.402-.112Z");
}

</style>

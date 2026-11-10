<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wypjoug_i"/><path class="jlsnwq2we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huantai-toolbox" /></template>
<style>
.jlsnwq2we {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.251 12.526v-2.2a2.36 2.36 0 0 1 2.354-2.367h12.778a2.36 2.36 0 0 1 2.366 2.354v2.212m-19.064 8.083c1.175 0 2.121 1.056 2.121 2.366v2.082c0 1.31-.946 2.366-2.121 2.366s-2.122-1.056-2.122-2.366v-2.082c0-1.31.947-2.366 2.122-2.366m20.63 0c1.175 0 2.122 1.056 2.122 2.366v2.082c0 1.31-.947 2.366-2.122 2.366s-2.121-1.056-2.121-2.366v-2.082c0-1.31.946-2.366 2.121-2.366m2.12 3.407h6.94m-27.568 0h16.386m-27.567 0h6.939");
}

.wypjoug_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.66 12.526h30.68a4.13 4.13 0 0 1 4.14 4.12V35.9a4.13 4.13 0 0 1-4.12 4.14H8.66a4.13 4.13 0 0 1-4.14-4.12V16.666a4.13 4.13 0 0 1 4.12-4.14z");
}

</style>

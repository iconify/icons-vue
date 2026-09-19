<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eot4t9bck"/><path class="n0s8u5b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ays" /></template>
<style>
.eot4t9bck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24v13.5M12.309 17.25L24 24l11.691-6.75");
}

.n0s8u5b3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21 3.305l-13.424 7.75a6 6 0 0 0-3 5.195v15.5a6 6 0 0 0 3 5.195L21 44.695a6 6 0 0 0 6 0l13.424-7.75a6 6 0 0 0 3-5.195v-15.5a6 6 0 0 0-3-5.195L27 3.305a6 6 0 0 0-6 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGCmKnMeWO" class="ug7f6gbga"/></defs><path class="mcq7zzf9u"/><use href="#SVGCmKnMeWO" class="c-zrgpb5l"/><use href="#SVGCmKnMeWO" class="c-zrgpb5l"/><path class="mth-69bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dbnavigator-beta" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mcq7zzf9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 30.572V9.162a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v21.41a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4");
}

.mth-69bhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.96 42.038c-.242.48-.807.8-1.373.8c-.888 0-1.615-.72-1.615-1.6v-1.04c0-.88.727-1.6 1.615-1.6c.89 0 1.616.72 1.616 1.6v.56h-3.232m5.318-3.76v5.006c0 .5.341.834.854.834h.256m-1.963-4.422h1.792m-11.45 1.669c0-.918.768-1.669 1.707-1.669s1.707.751 1.707 1.669v1.085c0 .917-.768 1.668-1.707 1.668s-1.707-.75-1.707-1.668m0 1.668v-6.674m16.444 5.006c0 .917-.769 1.668-1.707 1.668c-.94 0-1.708-.75-1.708-1.668v-1.085c0-.918.769-1.669 1.708-1.669c.938 0 1.707.751 1.707 1.669m0 2.753v-4.422");
}

.ug7f6gbga {
  fill: none;
  stroke: currentColor;
  d: path("M11.667 26.982v-15.18h2.466a7.61 7.61 0 0 1 7.59 7.59a7.61 7.61 0 0 1-7.59 7.59zM32.56 19.24a3.57 3.57 0 0 1 .003 7.14H26.67V12.1h5.89a3.57 3.57 0 0 1 0 7.14m0 0h-5.889");
}

</style>

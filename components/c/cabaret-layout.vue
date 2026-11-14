<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6r8c-eud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cabaret-layout" /></template>
<style>
.z6r8c-eud {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.934 5.184Q6.25 6.868 6.25 9.25t1.684 4.066T12 15t4.066-1.684T17.75 9.25t-1.684-4.066T12 3.5T7.934 5.184m-.667 8.091l.708.708q1.766 1.767.001 3.534l-.709.708q-1.767 1.766-3.534.001l-.708-.709q-1.766-1.767-.001-3.534l.709-.708q1.767-1.766 3.534-.001zm13.708.708l-.708-.708v-.001q-1.767-1.765-3.534.001l-.709.708q-1.765 1.767.001 3.534l.708.709q1.767 1.765 3.534-.001l.709-.708q1.765-1.767-.001-3.534M9 18.75q0-2.5 2.5-2.5h1q1.036 0 1.768.732T15 18.75v1q0 1.036-.732 1.768t-1.768.732h-1q-1.036 0-1.768-.732T9 19.75z");
}

</style>

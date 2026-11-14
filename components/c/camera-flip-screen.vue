<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyibg8y8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-flip-screen" /></template>
<style>
.oyibg8y8k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 8.5q0-1.139.805-1.945q.806-.805 1.945-.805h1.625L7.4 4.05q.052-.07.119-.126t.146-.095t.163-.059T8 3.75h3q.087 0 .172.02t.163.059q.079.039.146.095t.119.126l1.275 1.7H15.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.429l2.481-.902q1.1-.4 2.06.272q.959.672.959 1.843v8.716q0 1.171-.959 1.843q-.96.672-2.061.272l-2.483-.903q-.007.069-.026.136q-.019.066-.05.129q-.031.062-.073.117t-.093.102t-.11.084t-.124.061t-.133.038t-.138.013h-11q-2.75 0-2.75-2.75zm5.5.25q-2.5 0-2.5 2.5v2q0 1.036.732 1.768t1.768.732h3.5q1.036 0 1.768-.732t.732-1.768v-2q0-1.036-.732-1.768T10.75 8.75z");
}

</style>

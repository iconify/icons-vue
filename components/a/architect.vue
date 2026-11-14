<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjtzbgz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:architect" /></template>
<style>
.wjtzbgz9r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m8.371 15.25q-1.504 0-2.079-1.39t.489-2.451l5.877-5.878q1.063-1.064 2.452-.489t1.39 2.079V20q0 2.25-2.25 2.25zm-2.474-4.725l3.356-3.357q-1.938-.918-4.503-.918q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h6.852q-.825-2.106.795-3.725m2.474 3.225H20q.75 0 .75-.75v-5.879q0-.501-.463-.693t-.817.163l-5.879 5.878q-.354.355-.163.818q.192.463.693.463m4.629-1.25q0-1.502-.711-2.71l-2.711 2.71z");
}

</style>

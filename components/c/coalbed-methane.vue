<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5nc-ub0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coalbed-methane" /></template>
<style>
.s5nc-ub0j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.53 1.97q4.22 4.219 4.22 7.53q0 1.968-1.391 3.359q-.467.467-1 .777l2.274.91q.218.087.404.205q.062.003.122.016t.118.036q.057.023.11.054q.053.032.1.072t.086.088t.072.1q.031.053.054.111q.022.057.035.117q.017.08.016.162q.107.192.181.416l1.123 3.366q.363 1.093-.31 2.027t-1.825.934H3.797q-1.053-.001-1.727-.809t-.486-1.843l.556-3.064q.183-1.003 1.057-1.527h.001l3.086-1.852l.03-.018l.894-.536q.609-.365 1.317-.315l2.775.198q-1.05-1.275-1.05-2.984q0-2.811 2.22-5.03q.105-.106.243-.163T13 4.25q.137 0 .266.049t.231.14q.126-1.418.917-2.408q.094-.116.224-.188q.131-.072.279-.088q.148-.017.292.025q.143.041.26.134q.032.026.061.056");
}

</style>

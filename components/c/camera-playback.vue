<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o04696liu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-playback" /></template>
<style>
.o04696liu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.555 5.055Q1.75 5.861 1.75 7v9.5q0 2.75 2.75 2.75H14v-1.121q-.001-2.032 1.765-3.04t3.515.026h.001l.969.573V7q0-2.75-2.75-2.75h-2.075l-1.282-2.136q-.05-.083-.119-.151q-.07-.068-.154-.116q-.085-.048-.179-.072q-.094-.025-.191-.025h-5q-.097 0-.191.025q-.094.024-.179.072t-.154.116t-.119.151L6.575 4.25H4.5q-1.139 0-1.945.805M7.25 11.5q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5m11.395 4.691l1.052.622q1.104.654 1.104 1.937t-1.104 1.937l-1.052.622q-1.126.664-2.261.017q-1.134-.648-1.134-1.955v-1.242q0-1.307 1.134-1.955q1.135-.647 2.261.017m-.764 1.292q-.375-.222-.753-.006t-.378.652v1.242q0 .436.378.652t.753-.006l1.052-.622q.368-.217.368-.645t-.368-.645z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ai3jzlbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-microphone-above-16-filled" /></template>
<style>
.ai3jzlbdj {
  fill: currentColor;
  d: path("M5.17 13.672a4 4 0 0 1 5.657 0a.5.5 0 0 1-.707.707a3 3 0 0 0-4.243 0a.5.5 0 1 1-.707-.707m-1.766-1.768a6.5 6.5 0 0 1 9.193 0a.5.5 0 0 1-.707.707a5.5 5.5 0 0 0-7.779 0a.5.5 0 1 1-.707-.707M8 4c1.74 0 3.29.327 4.387.833C13.526 5.359 14 5.984 14 6.5q-.002.053-.008.105c-.06.494-.543 1.072-1.605 1.562C11.29 8.673 9.735 9 8 9s-3.29-.327-4.387-.833c-1.062-.49-1.546-1.068-1.606-1.562Q2 6.553 2 6.5c0-.516.474-1.141 1.613-1.667C4.71 4.327 6.261 4 8 4m0-3c1.561 0 2.996.23 4.06.616c.529.193.993.434 1.334.727c.338.291.606.68.606 1.157v1.158a5.5 5.5 0 0 0-1.194-.733C11.55 3.345 9.85 3 8 3s-3.55.345-4.806.925c-.44.203-.85.449-1.194.733V3.5c0-.477.267-.866.606-1.157c.341-.293.805-.534 1.334-.727C5.003 1.23 6.44 1 8 1");
}

</style>

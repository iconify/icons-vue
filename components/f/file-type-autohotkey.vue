<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGqRV9sb9o" x1="54.604" x2="54.604" y1="168.388" y2="194.885" gradientTransform="translate(-38.604 -165.636)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xfxkbyxzk"/><stop offset="1" class="oxgxalihh"/></linearGradient><linearGradient id="SVGQHo6ec9p" x1="68.756" x2="91.638" y1="209.152" y2="209.152" gradientTransform="matrix(.832 0 0 .837 -50.601 -159.449)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cg6k03bex"/><stop offset=".5" class="oqyi0mnfp"/><stop offset="1" class="cg6k03bex"/></linearGradient></defs><rect fill="url(#SVGqRV9sb9o)" class="wi58l_r3p"/><path class="w4qo3403k"/><rect fill="url(#SVGQHo6ec9p)" class="hxjjigbuc"/><path class="vp5l_7brn"/><path class="q3lduvmio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-autohotkey" /></template>
<style>
.cg6k03bex {
  stop-color: var(--svg-color--d7d7d7, #d7d7d7);
}

.hxjjigbuc {
  width: 23.169px;
  height: 21.94px;
  x: 4.313px;
  y: 4.641px;
  rx: 2.571px;
  ry: 2.571px;
}

.oqyi0mnfp {
  stop-color: var(--svg-color--e7e7e7, #e7e7e7);
}

.oxgxalihh {
  stop-color: var(--svg-color--a3a3a3, #a3a3a3);
}

.q3lduvmio {
  d: path("m6.145 23.9l2.343-6.1h.87l2.5 6.1h-.92l-.712-1.848H7.673L7 23.9ZM7.9 21.4h2.074l-.637-1.7q-.291-.77-.433-1.265a8 8 0 0 1-.328 1.165Zm5.707 2.5v-6.1h.807v2.5h3.171v-2.5h.807v6.1h-.807v-2.879h-3.17V23.9Zm6.871 0v-6.1h.807v3.025l3.03-3.025h1.094l-2.559 2.467l2.672 3.633h-1.066l-2.172-3.088l-1 .974V23.9Z");
}

.vp5l_7brn {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M24.911 26.641H6.884a2.634 2.634 0 0 1-2.631-2.631V7.212a2.634 2.634 0 0 1 2.631-2.631h18.027a2.634 2.634 0 0 1 2.631 2.631v16.8a2.634 2.634 0 0 1-2.631 2.629M6.884 4.7a2.514 2.514 0 0 0-2.511 2.512v16.8a2.514 2.514 0 0 0 2.511 2.511h18.027a2.514 2.514 0 0 0 2.511-2.511v-16.8A2.514 2.514 0 0 0 24.911 4.7Z");
}

.w4qo3403k {
  fill: var(--svg-color--8d8d8d, #8d8d8d);
  d: path("M26.856 29.181H5.144A3.15 3.15 0 0 1 2 26.037V5.963a3.15 3.15 0 0 1 3.144-3.144h21.712A3.15 3.15 0 0 1 30 5.963v20.074a3.15 3.15 0 0 1-3.144 3.144M5.144 2.963a3 3 0 0 0-3 3v20.074a3 3 0 0 0 3 3h21.712a3 3 0 0 0 3-3V5.963a3 3 0 0 0-3-3Z");
}

.wi58l_r3p {
  width: 28px;
  height: 26.353px;
  x: 2px;
  y: 2.824px;
  rx: 3.088px;
  ry: 3.088px;
}

.xfxkbyxzk {
  stop-color: var(--svg-color--d8d8d8, #d8d8d8);
}

</style>

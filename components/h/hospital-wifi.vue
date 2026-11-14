<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w9w0r7beg"/><path class="n0q0gac6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hospital-wifi" /></template>
<style>
.n0q0gac6b {
  fill: currentColor;
  d: path("M16.5 14.25h3v2.25h2.25v3H19.5v2.25h-3V19.5h-2.25v-3h2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9w0r7beg {
  d: path("M2.608 8.69a11.5 11.5 0 0 1 14.784 0M5.018 11.563q.127-.107.259-.208t.268-.197t.275-.185t.284-.173q.143-.083.291-.161q.147-.077.297-.148t.303-.135t.309-.122t.314-.109t.318-.096t.322-.081q.162-.038.325-.068q.164-.03.328-.054q.164-.023.33-.039q.165-.016.331-.026t.332-.011q.166-.002.332.003t.332.017q.165.013.33.032t.329.045t.327.06q.163.033.324.074t.321.087q.159.047.316.101t.312.114t.306.128t.301.141t.295.154t.288.166t.28.178t.272.19t.264.201m-7.404 2.995q.203-.17.426-.312q.224-.142.464-.253t.492-.19q.253-.079.514-.123q.261-.045.525-.055q.265-.01.528.015q.264.025.522.085q.258.059.505.152M10 17.5h.01");
}

</style>

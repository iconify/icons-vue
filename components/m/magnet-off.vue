<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huew5_q7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnet-off" /></template>
<style>
.huew5_q7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 13.476V21H4V11q0-1.364.452-2.65m3.543-4.276q.455-.262.94-.463q.485-.202.992-.338t1.027-.204T12 3q.196 0 .393.01q.196.009.391.029q.196.019.39.048q.194.028.387.067q.192.038.383.086q.19.047.378.104t.373.124q.185.066.366.141q.182.075.359.159q.178.084.351.177t.342.193q.168.101.332.21q.163.109.321.226q.157.117.309.242t.297.256q.146.132.285.271t.271.285q.131.145.256.297t.242.309q.117.158.226.321q.109.164.21.332q.101.169.193.342q.093.173.177.351q.084.177.159.359q.075.181.141.366q.067.185.124.373t.104.378t.086.383t.067.387t.048.39t.029.391q.01.197.01.393v5.029M17.071 21H14.5v-2.529m-.051-7.975q-.038-.181-.101-.354t-.151-.335t-.199-.309t-.241-.277t-.28-.238t-.312-.195t-.337-.147q-.173-.061-.354-.096M4 16.5h5.5m-6-13l17 17");
}

</style>

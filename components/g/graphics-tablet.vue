<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssrj5tb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:graphics-tablet" /></template>
<style>
.ssrj5tb8q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h10q1.76 0 3.005 1.245T20.25 7v5q0 1.271-.649 2.273l-1.633-1.633q-.709-.71-1.688-.936l-1.204-.278h-.002q-1.642-.379-2.835.813q-1.193 1.193-.813 2.835l.271 1.176H6q-1.76 0-3.005-1.245T1.75 12V7q0-1.76 1.245-3.005T6 2.75m8.793 9.894l1.205.278q.629.146 1.085.602l4.135 4.135q.66.659.66 1.591t-.66 1.592l-.378.377q-.659.66-1.591.66t-1.592-.66l-4.134-4.135q-.456-.456-.602-1.084l-.278-1.207q-.224-.967.479-1.67q.703-.702 1.67-.479m-.337 1.462q-.158-.037-.272.078t-.078.273l.278 1.205q.048.21.2.362l4.136 4.135q.219.22.53.22t.531-.22l.378-.379q.22-.219.22-.53t-.22-.531l-4.135-4.135q-.152-.152-.361-.2z");
}

</style>

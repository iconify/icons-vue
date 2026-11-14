<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnikt1o6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beer-stein" /></template>
<style>
.vnikt1o6j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 9.878v1.372h1.25q3.25 0 3.25 3.25V16q0 3.25-3.25 3.25h-1.256q-.122 2.5-2.744 2.5h-7q-2.75 0-2.75-2.75V9.838Q2.491 8.621 3.044 6.85q.524-1.677 2.102-2.021q.584-1.843 2.62-2.25q1.829-.366 3.022.789q1.243-1.034 2.99-.451q1.998.666 2.199 2.627q1.085.697 1.183 2.078q.101 1.406-.91 2.256M14.75 19v-8.75h-9.5V19q0 1.25 1.25 1.25h7q1.25 0 1.25-1.25m2.75-6.25h-1.25v5h1.25q1.75 0 1.75-1.75v-1.5q0-1.75-1.75-1.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi53psbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cylinder" /></template>
<style>
.wi53psbfx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.418 3.182Q3.75 4.25 3.75 6v12q0 1.75 2.668 2.818q2.331.932 5.582.932t5.582-.932Q20.25 19.75 20.25 18V6q0-1.75-2.668-2.818Q15.251 2.25 12 2.25t-5.582.932M5.25 18V8.241q.501.31 1.168.577Q8.749 9.75 12 9.75t5.582-.932q.667-.267 1.168-.577V18q0 .735-1.725 1.425q-2.063.825-5.025.825t-5.025-.825Q5.25 18.735 5.25 18");
}

</style>

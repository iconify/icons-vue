<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_68_fb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chatbot-quick-replies" /></template>
<style>
.p_68_fb5g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 4.5q0-1.139.805-1.945q.806-.805 1.945-.805h15q2.75 0 2.75 2.75v3q0 2.75-2.75 2.75H8.272L5.48 12.576q-.057.047-.121.083q-.065.035-.136.057q-.07.022-.144.03t-.147.001t-.144-.028t-.137-.055t-.122-.081q-.058-.046-.105-.103q-.084-.101-.129-.225q-.045-.123-.045-.255v-1.756q-2.5-.122-2.5-2.744zM20 12h-9q-2.25 0-2.25 2.25T11 16.5h9q2.25 0 2.25-2.25T20 12m-9 6h9q2.25 0 2.25 2.25T20 22.5h-9q-2.25 0-2.25-2.25T11 18");
}

</style>

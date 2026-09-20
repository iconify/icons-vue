<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue6zcz-ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:breakout-room-24-filled" /></template>
<style>
.ue6zcz-ut {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21h-5.036A4.73 4.73 0 0 0 14 17.75v-3A4.75 4.75 0 0 0 9.25 10h-3c-1.257 0-2.4.488-3.25 1.286zm0 8.5v3A3.25 3.25 0 0 0 6.25 21h3a3.25 3.25 0 0 0 3.25-3.25v-3a3.25 3.25 0 0 0-3.25-3.25h-3A3.25 3.25 0 0 0 3 14.75");
}

</style>

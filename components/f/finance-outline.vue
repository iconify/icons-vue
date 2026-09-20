<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4yl9gozc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:finance-outline" /></template>
<style>
.j4yl9gozc {
  fill: currentColor;
  d: path("M5.116 20q-.691 0-1.153-.462T3.5 18.384V3h1v15.385q0 .23.192.423t.423.192H20.5v1zm2.269-3.5V9.192h2V16.5zm4.5 0V4.192h2V16.5zm4.5 0v-3.308h2V16.5z");
}

</style>

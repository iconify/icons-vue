<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqbqmib-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-4-bar" /></template>
<style>
.dqbqmib-l {
  fill: currentColor;
  d: path("M8.696 21q-.352 0-.581-.232q-.23-.233-.23-.576V5.288q0-.343.232-.575t.575-.232h1.616V3h3.384v1.48h1.62q.344 0 .574.233q.23.232.23.576v14.903q0 .344-.233.576t-.575.232zm.189-9h6.23V5.462h-6.23z");
}

</style>

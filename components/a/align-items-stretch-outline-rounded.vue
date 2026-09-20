<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a57t3mb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-items-stretch-outline-rounded" /></template>
<style>
.a57t3mb3s {
  fill: currentColor;
  d: path("M8.308 17.5q-.343 0-.576-.232t-.232-.576V7.308q0-.343.232-.576t.576-.232h.384q.344 0 .576.232t.232.576v9.384q0 .344-.232.576t-.576.232zm7 0q-.343 0-.576-.232t-.232-.576V7.308q0-.343.232-.576t.576-.232h.384q.344 0 .576.232t.232.576v9.384q0 .344-.232.576t-.576.232zM3.5 21q-.213 0-.356-.144T3 20.499t.144-.356T3.5 20h17q.213 0 .356.144t.144.357t-.144.356T20.5 21zm0-17q-.213 0-.356-.144T3 3.499t.144-.356T3.5 3h17q.213 0 .356.144t.144.357t-.144.356T20.5 4z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m8c8lfbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-person-20-filled" /></template>
<style>
.m8c8lfbul {
  fill: currentColor;
  d: path("M16.5 14a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S11 16.75 11 15.5a1.5 1.5 0 0 1 1.5-1.5zM10.669 2c-.307.343-.54.759-.665 1.227l-3.438 12.89a.501.501 0 0 0 .967.258l3.438-12.89a2 2 0 0 1 1.81-1.48a3 3 0 0 1 2.375 1.394l3.574 5.667c.36.57.36 1.297 0 1.868l-1.395 2.212a2.5 2.5 0 0 0-.608-.136a3 3 0 1 0-4.767-3.603l1.476-5.527a.5.5 0 0 0-.966-.258L9.03 16.516a2 2 0 0 1-1.813 1.48A3 3 0 0 1 4.84 16.6l-3.574-5.667a1.75 1.75 0 0 1 0-1.868l3.941-6.25a1.75 1.75 0 0 1 1.48-.816zM14.5 9a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>

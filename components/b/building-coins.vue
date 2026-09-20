<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e_a77p50x.css';
import '../../css/m/mlhujcbev.css';
import '../../css/n/n7f7_pbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e_a77p50x"/><path class="mlhujcbev"/><path clip-rule="evenodd" class="n7f7_pbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:building-coins" /></template>

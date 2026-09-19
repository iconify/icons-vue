<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7-k3vx_v.css';
import '../../css/t/txo8pobhd.css';
import '../../css/m/mtna5qb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p7-k3vx_v"/><path class="txo8pobhd"/><path class="mtna5qb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-radial" /></template>

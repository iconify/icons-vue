<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spu-vnbsz.css';
import '../../css/r/r4k-7obry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="spu-vnbsz"/><path class="r4k-7obry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:box-cutter-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pore5-dgs.css';
import '../../css/r/r6ewlybsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pore5-dgs"/><path class="r6ewlybsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frame-20-bold" /></template>

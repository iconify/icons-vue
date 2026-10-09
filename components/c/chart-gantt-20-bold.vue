<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luzrlq7wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="luzrlq7wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-gantt-20-bold" /></template>

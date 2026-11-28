<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjz1akfte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjz1akfte primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:line-chart-sparkles-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fens4lu3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fens4lu3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:line-chart-arrow-down" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8d3vob2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8d3vob2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:growth-chart-stroke-16" /></template>

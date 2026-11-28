<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk2y3hezu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk2y3hezu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:donut-chart-search" /></template>

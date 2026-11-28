<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgb017bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgb017bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:line-chart-search" /></template>

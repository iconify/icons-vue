<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy06a2osb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy06a2osb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-chart-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytt8pvboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytt8pvboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-scatter-3d" /></template>

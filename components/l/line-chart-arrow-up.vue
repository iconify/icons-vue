<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8acfk1bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8acfk1bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:line-chart-arrow-up" /></template>

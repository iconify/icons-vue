<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeibzhb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeibzhb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:donut-chart-fill" /></template>

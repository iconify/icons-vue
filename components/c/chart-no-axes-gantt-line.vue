<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrpzbvbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrpzbvbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-no-axes-gantt-line" /></template>

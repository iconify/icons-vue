<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sijc31_mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sijc31_mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-column-stacked-line" /></template>

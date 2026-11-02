<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqcf3038h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqcf3038h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-stacked-fill" /></template>

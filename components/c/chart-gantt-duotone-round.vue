<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyno9_3-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyno9_3-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-gantt-duotone-round" /></template>

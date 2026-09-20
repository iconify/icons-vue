<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qginy2b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qginy2b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-gantt" /></template>

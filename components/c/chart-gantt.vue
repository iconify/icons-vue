<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fajw8b66w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fajw8b66w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-gantt" /></template>

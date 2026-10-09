<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a82m3kbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a82m3kbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-gantt-48" /></template>

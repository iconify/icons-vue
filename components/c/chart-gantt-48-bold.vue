<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg5if1byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sg5if1byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-gantt-48-bold" /></template>

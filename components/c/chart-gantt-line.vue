<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6r3u_hfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6r3u_hfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-gantt-line" /></template>

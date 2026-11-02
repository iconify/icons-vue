<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no7fnibtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no7fnibtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-no-axes-gantt-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbs7r8msg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbs7r8msg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-chart-column-increasing-fill" /></template>

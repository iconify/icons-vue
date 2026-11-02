<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u74c4ybvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u74c4ybvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-chart-pie-fill" /></template>

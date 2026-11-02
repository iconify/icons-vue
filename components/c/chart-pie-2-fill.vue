<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izwoc4b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izwoc4b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-2-fill" /></template>

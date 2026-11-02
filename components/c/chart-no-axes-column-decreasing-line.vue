<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qikfyukbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qikfyukbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-no-axes-column-decreasing-line" /></template>

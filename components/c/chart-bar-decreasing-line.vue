<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdaw-weoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdaw-weoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-decreasing-line" /></template>

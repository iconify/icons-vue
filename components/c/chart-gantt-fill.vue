<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb8uykbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb8uykbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-gantt-fill" /></template>

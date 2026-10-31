<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl_cu4b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl_cu4b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kanban-round" /></template>

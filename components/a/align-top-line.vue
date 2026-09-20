<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zenmd1bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zenmd1bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-top-line" /></template>

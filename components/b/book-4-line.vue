<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unfj3cbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unfj3cbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-4-line" /></template>

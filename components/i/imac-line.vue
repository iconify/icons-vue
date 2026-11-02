<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb3lsv9dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb3lsv9dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:imac-line" /></template>

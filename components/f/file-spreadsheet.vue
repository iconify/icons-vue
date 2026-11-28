<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdyx0-b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdyx0-b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-spreadsheet" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d94hp_bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d94hp_bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-spreadsheet-line" /></template>

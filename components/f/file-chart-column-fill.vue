<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctd_733kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctd_733kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-chart-column-fill" /></template>

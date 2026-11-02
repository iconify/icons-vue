<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0pmbdb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0pmbdb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-column-decreasing-line" /></template>

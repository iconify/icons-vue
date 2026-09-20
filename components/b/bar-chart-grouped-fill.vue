<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs5hjpbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs5hjpbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bar-chart-grouped-fill" /></template>

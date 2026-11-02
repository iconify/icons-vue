<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttyc_3k6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttyc_3k6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-scatter-line" /></template>

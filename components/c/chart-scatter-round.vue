<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8314ccnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8314ccnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-scatter-round" /></template>

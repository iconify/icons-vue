<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5-m_mbgb.css';
import '../../css/i/i68tsac5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f5-m_mbgb"/><path class="i68tsac5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-network-20" /></template>

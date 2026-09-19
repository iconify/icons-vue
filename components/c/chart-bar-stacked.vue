<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwc79vbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lwc79vbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-bar-stacked" /></template>

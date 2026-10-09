<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-_cnnjai.css';
import '../../css/q/qi1j3qboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h-_cnnjai"/><path class="qi1j3qboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-sankey-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6m34_-qc.css';
import '../../css/h/h-3i78bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6m34_-qc"/><path class="h-3i78bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:automatic" /></template>

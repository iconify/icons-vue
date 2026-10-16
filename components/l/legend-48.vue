<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5b9qsji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zw5b9qsji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:legend-48" /></template>

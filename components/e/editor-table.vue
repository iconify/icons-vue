<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5jvbwbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y5jvbwbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-table" /></template>

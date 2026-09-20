<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjxhmxtgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="vjxhmxtgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:drag-vertical" /></template>

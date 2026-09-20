<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds--vq8wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds--vq8wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-undo-outline" /></template>

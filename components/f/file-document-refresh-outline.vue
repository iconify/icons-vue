<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iced0ob2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iced0ob2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-refresh-outline" /></template>

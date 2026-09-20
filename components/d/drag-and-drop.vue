<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd_z6iuxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd_z6iuxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:drag-and-drop" /></template>

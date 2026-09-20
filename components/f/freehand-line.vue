<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asln6lbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asln6lbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:freehand-line" /></template>

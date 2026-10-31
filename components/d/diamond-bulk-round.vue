<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vey7pvboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vey7pvboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-bulk-round" /></template>

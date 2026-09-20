<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgn9s7blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgn9s7blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chart-minus" /></template>

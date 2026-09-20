<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wee52ogfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wee52ogfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:drag-and-drop-solid" /></template>

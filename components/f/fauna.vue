<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkvzy8bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkvzy8bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fauna" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyjp9ub1w.css';
import '../../css/p/pdfzy9j9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyjp9ub1w"/><path class="pdfzy9j9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-waterdrop-bold" /></template>

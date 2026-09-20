<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzy8njb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzy8njb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-send-light" /></template>

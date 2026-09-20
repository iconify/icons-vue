<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9lsp2bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9lsp2bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:image-in-picture-line" /></template>

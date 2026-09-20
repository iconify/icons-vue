<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddebkccpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddebkccpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-search-fill" /></template>

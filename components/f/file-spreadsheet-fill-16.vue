<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8qoe7bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d8qoe7bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-spreadsheet-fill-16" /></template>

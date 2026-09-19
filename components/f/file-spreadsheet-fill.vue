<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvw4nff7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zvw4nff7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-spreadsheet-fill" /></template>

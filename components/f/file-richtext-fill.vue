<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1bbxobxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y1bbxobxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-richtext-fill" /></template>

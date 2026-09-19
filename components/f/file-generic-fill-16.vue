<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vts6m5b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vts6m5b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-generic-fill-16" /></template>

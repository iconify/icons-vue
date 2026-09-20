<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnz4v1b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nnz4v1b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:handle" /></template>

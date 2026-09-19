<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjsfgvb4f.css';
import '../../css/u/unp6d04od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zjsfgvb4f"/><path class="unp6d04od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eraser-fill-12" /></template>

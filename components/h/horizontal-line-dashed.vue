<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3kdhjb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h3kdhjb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:horizontal-line-dashed" /></template>

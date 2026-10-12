<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4vlptxqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e4vlptxqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-left-20" /></template>

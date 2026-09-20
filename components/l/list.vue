<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/filwcgb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="filwcgb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:list" /></template>

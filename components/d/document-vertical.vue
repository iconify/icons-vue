<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0vo7tb2u.css';
import '../../css/v/vy9mlrb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0vo7tb2u"/><path class="vy9mlrb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-vertical" /></template>

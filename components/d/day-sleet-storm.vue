<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_a6-ubkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="d_a6-ubkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:day-sleet-storm" /></template>

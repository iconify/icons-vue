<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5sx-kk8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d5sx-kk8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chart-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl1y2kbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl1y2kbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-sort-descending" /></template>

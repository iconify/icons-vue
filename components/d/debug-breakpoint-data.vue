<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vouatzbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vouatzbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-data" /></template>

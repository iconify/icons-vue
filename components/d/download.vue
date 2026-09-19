<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxa7t1amh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cxa7t1amh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:download" /></template>

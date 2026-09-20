<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8v7vu7pd.css';
import '../../css/i/i_73qioux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c8v7vu7pd"/><path class="i_73qioux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-trigger" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5_5zcc8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o5_5zcc8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:diff-single" /></template>

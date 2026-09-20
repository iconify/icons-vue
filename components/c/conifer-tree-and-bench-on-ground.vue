<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoyi7uoos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uoyi7uoos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-and-bench-on-ground" /></template>

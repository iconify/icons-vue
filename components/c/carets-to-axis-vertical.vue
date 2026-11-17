<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0dfs_59j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0dfs_59j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:carets-to-axis-vertical" /></template>

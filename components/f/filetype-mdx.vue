<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7jx4s0fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7jx4s0fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-mdx" /></template>

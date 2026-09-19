<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr6_cjb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zr6_cjb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-jsx" /></template>

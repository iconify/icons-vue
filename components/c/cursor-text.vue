<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziba7sb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ziba7sb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:cursor-text" /></template>

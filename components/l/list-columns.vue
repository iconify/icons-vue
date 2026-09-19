<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arn344fbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="arn344fbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:list-columns" /></template>

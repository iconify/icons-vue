<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytdk_ib9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ytdk_ib9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:line-height-fill" /></template>

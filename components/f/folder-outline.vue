<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_qqtdbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d_qqtdbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:folder-outline" /></template>

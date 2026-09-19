<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nla6sw03w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nla6sw03w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drag-horizontal" /></template>

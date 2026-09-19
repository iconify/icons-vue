<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi-jphbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vi-jphbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:line-graph-fill-12" /></template>

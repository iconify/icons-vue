<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1k29ppvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d1k29ppvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:home-stroke-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1l6yn6av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i1l6yn6av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-write" /></template>

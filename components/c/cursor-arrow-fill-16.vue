<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e01znbbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e01znbbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cursor-arrow-fill-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvb739bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvb739bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:graph-left" /></template>

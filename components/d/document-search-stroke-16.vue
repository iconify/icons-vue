<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cptwmsbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cptwmsbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:document-search-stroke-16" /></template>

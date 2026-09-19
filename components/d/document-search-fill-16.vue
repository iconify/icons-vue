<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skzakomwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="skzakomwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:document-search-fill-16" /></template>

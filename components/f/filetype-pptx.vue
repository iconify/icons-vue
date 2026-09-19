<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be7pepbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="be7pepbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-pptx" /></template>

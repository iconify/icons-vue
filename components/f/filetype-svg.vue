<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlbam1fih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zlbam1fih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-svg" /></template>

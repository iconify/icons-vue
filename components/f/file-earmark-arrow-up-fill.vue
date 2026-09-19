<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dglssse0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dglssse0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-arrow-up-fill" /></template>

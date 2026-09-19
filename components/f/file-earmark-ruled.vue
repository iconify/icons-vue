<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2cpz77ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g2cpz77ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-ruled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt04mfb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wt04mfb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:magnifying-glass-x" /></template>

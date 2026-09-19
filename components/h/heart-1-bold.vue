<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl08a40-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cl08a40-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-1-bold" /></template>

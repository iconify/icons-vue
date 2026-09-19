<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvvvaq5nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dvvvaq5nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fire-1-outline" /></template>

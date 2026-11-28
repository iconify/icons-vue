<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9pp1fbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d9pp1fbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-slash-bold" /></template>

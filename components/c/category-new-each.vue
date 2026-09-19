<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s99tybc2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s99tybc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:category-new-each" /></template>

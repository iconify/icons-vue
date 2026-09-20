<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bag6wvkzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bag6wvkzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:collapse" /></template>

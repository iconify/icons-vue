<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw6fp4b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bw6fp4b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inbox-add" /></template>

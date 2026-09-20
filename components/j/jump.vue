<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnnn5it5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gnnn5it5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:jump" /></template>

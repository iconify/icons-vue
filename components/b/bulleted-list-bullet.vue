<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0t74x1cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i0t74x1cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bulleted-list-bullet" /></template>

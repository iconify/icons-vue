<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6yy8jbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j6yy8jbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:border-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je0ehx_fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="je0ehx_fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-crossover-left-remix" /></template>

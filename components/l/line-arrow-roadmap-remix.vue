<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa248iygj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fa248iygj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:line-arrow-roadmap-remix" /></template>

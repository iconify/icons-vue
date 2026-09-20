<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zci6vmbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zci6vmbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-position-bottom-right" /></template>

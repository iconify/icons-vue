<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obgjjz6ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obgjjz6ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:fold" /></template>

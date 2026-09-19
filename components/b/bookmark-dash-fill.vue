<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofkr7ob2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ofkr7ob2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bookmark-dash-fill" /></template>

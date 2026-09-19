<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_9nzdb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d_9nzdb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:lib" /></template>

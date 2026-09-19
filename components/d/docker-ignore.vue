<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5amb42ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j5amb42ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:docker-ignore" /></template>

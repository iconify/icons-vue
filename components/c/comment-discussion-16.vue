<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly8u96qqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ly8u96qqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment-discussion-16" /></template>

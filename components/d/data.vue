<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3b_-jb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j3b_-jb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:data" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b08klq9nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b08klq9nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-unordered-list" /></template>

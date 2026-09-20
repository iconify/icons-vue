<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyac__b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fyac__b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-tree-sub" /></template>

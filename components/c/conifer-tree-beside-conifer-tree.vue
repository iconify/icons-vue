<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm4js56by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zm4js56by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-beside-conifer-tree" /></template>

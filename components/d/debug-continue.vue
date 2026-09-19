<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8gbhxr-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h8gbhxr-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-continue" /></template>

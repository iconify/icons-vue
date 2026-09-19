<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6zuvtb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m6zuvtb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:diff-modified" /></template>

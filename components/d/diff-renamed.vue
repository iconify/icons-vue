<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxan0itcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jxan0itcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:diff-renamed" /></template>

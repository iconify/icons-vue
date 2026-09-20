<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzyuwrbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qzyuwrbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-modified-16" /></template>

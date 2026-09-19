<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5mp5wb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z5mp5wb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-continue-small" /></template>

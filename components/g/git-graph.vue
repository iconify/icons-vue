<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc64bdcbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wc64bdcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:git-graph" /></template>

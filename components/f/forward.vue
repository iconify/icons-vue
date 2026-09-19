<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n93xk4ohs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n93xk4ohs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:forward" /></template>

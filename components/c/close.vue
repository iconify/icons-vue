<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtd8ioskf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dtd8ioskf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:close" /></template>

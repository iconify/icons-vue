<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdxbqq0sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fdxbqq0sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-plus" /></template>

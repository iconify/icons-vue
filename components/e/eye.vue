<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0w565bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c0w565bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:eye" /></template>

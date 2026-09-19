<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa5x1dblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sa5x1dblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-vis-4" /></template>

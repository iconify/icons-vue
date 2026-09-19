<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0q5nbr5o.css';
import '../../css/e/ebeqjhxfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z0q5nbr5o"/><path class="ebeqjhxfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:image-search" /></template>
